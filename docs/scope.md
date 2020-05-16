# Scope / learnings

## What is currently working?

* use mkdocs to generate static HTML pages
* mkdocs is triggered by github actions, then pushed to gh-pages branch
* push event notifies a webhook that pulls for deployment on primary hosting

## questions

* can this setup git-lfs?
* ~~does plesk really need an SSH key?~~ not if you use HTTPS to clone
