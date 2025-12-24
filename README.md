# Git-Commands

# Pushing Files from a local VM to a Github Empty Repo

1. Make a empty repo on github

2. On local VM 

1.  Clone the github repo

        git clone repo-link

2. Go into that repo

       cd repo

3. Initiate the empty git repo on the local VM.

       git init

4. Do this to set the identity in this repo ( use without global ) or globally. It's only for one time on the same machine.

       git config --global user.email "you@example.com"

       git config --global user.name "Your Name"


<img width="686" height="203" alt="image" src="https://github.com/user-attachments/assets/5b69fdeb-e15e-4654-9526-cd8635b3772e" />


5. Copy the files from the VM path into this repo.

       cp /path .

6. Do git pull to be in sync with the remote git repo, if any other commits have done there , so you can have them in your local repo

       git pull --rebase

7. Add the files

       git add .

8. Check the git status

       git status

9. Commit the changes 

       git commit -m "Your message"

10. Add a remote repo to your local VM

        git add remote origin github-repo-url

11. See the remote repo branch 

        git branch -r

12. See on which branch you are currently

        git branch

13. If different, write the name of the branch as well in this push andd Push the changes to this remote repo

        git push -u origin main

14. Fetch remote updates

        git fetch origin







