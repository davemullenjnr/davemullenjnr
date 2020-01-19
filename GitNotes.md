---
published: false
---

# Git Notes

## View site in production mode (with Cloudinary images loading)
    JEKYLL_ENV=production bundle exec jekyll serve

## Run server to generate local site
    jekyll serve

## Stop server
    ctrl-c

## See what files have been modified
    git status

## Push local changes to GitHub
    git add .  
    git commit -m "description"  
    git push

## Setting your local branch to exactly match the remote branch
    git fetch origin
    git reset --hard origin/master

## Update Gems
    bundle update

## The current folder will be generated into site folder
    jekyll build

##  The current folder will be generated into site folder, watched for changes, and regenerated automatically.
    jekyll build --watch

***

# Updates
## Look up outdated gems
    gem outdated

## Update Jekyll dependancies
    bundle update jekyll
