# general notes

## what is currently working?

* use mkdocs to generate static HTML pages
* use requirements.txt to enable extensions
* mkdocs is triggered by github actions, then pushed to gh-pages branch
* push event notifies a webhook that pulls for deployment on primary hosting
* gh actions are taken from fork for security reasons

## questions

* can this setup git-lfs?
* ~~does plesk really need an SSH key?~~ not if you use HTTPS to clone
