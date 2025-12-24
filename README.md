# Git-Commands

# Pushing Files from a local VM to a Github Empty Repo

Make a empty repo on github

On local VM 

Clone the github repo

git clone repo-link

Go into that repo

Initiate the empty git repo on the local VM.

git init

Do this to set the identity in this repo ( use without global ) or globally. It's only for one time on the same machine.

git config --global user.email "you@example.com"
git config --global user.name "Your Name"


<img width="686" height="203" alt="image" src="https://github.com/user-attachments/assets/5b69fdeb-e15e-4654-9526-cd8635b3772e" />


Copy the files from the VM path into this repo.

cp /path .

Do git pull to be in sync with the remote git repo, if any other commits have done there , so you can have them in your local repo

git pull --rebase

Add the files

git add .

Check the git status

git status

Commit the changes 

git commit -m "Your message"

Add a remote repo to your local VM

git add remote origin github-repo-url

See the remote repo branch 

git branch -r

See on which branch you are currently

git branch

If different, write the name of the branch as well in this push andd Push the changes to this remote repo

git push -u origin main

Fetch remote updates

git fetch origin







