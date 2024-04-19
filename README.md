# Survival_Island

## To Run This Repository:

get .umap and .uasset files from git lfs after downloading the project

###Prerequisites

if cloning:
1. `git lfs install`
2. `git clone https://github.com/sideOfBeans/Survival_Island.git`

if downloaded from a zip file: (please just clone the repo since LFS is being used)
1. `git init`
2. `git remote add origin https://github.com/sideOfBeans/Survival_Island.git`
3. `git clean -fdx`
4. `git lfs install`
5. `git pull origin main`
6. if that doesn't work, then try: `git branch -m master main` to rename the original branch from master to main and pull again

if pulling:
1. `git lfs install`
2. `git stash`
3. `git pull origin main`
4. `git stash apply` (optional; if you want to add back your own changes)



to get git lfs:
https://github.com/git-lfs/git-lfs/blob/main/INSTALLING.md
`curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash`
`sudo apt-get install git-lfs`
for linux

taken from:
https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage
and
https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
then,
`git lfs install`
finally, to pull changes from git lfs to replace text pointers with proper .uasset and .umap files:
`git lfs pull`
or use normal git commands like `git pull`

Developed with Unreal Engine 5
