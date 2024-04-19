# Survival_Island

## To Run This Repository:

get .umap and .uasset files from git lfs after downloading the project

###Prerequisites

if downloaded from a zip file:
1. `git init`
2. `git remote add origin https://github.com/sideOfBeans/Survival_Island.git`
3. `git pull origin main`

if that doesn't work, then try: `git branch -m master main` to rename the original branch from master to main

to get git lfs:
https://github.com/git-lfs/git-lfs/blob/main/INSTALLING.md
`curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash`
`sudo apt-get install git-lfs`
for ubuntu

taken from:
https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage
and
https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
then,
`git lfs install`
finally, to pull changes from git lfs to replace text pointers with proper .uasset and .umap files:
`git lfs pull`

Developed with Unreal Engine 5
