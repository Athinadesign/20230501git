 20230105git

- git init: intialize git repository (repo)
	-do not nest git repositories

- git status: provide you info about what's going on

- git add

- git commit
  - git commit -m "My message"

- git log
   git log --oneline

- HEAD: tells you where you are

- git diff: shows new changes to repo
   - git diff --stages: show changes in staging
   - git diff <HASH> <FILE> : you can pass hash value and opt. file - compare 2 states	

- git checkout <HASH> : move head to hash
  - you will be in a detached HEAD state
  - git switch main OR git checkout main -- to reattach head?

-Delete README.md file 
 -- this can also be reverting previous file state
- git status: this is your friend
- git restore HASH FILE : to revert file to pre commit stage
- git checkout HASH FILE: rever file from any point in time
- git restore --source=HASH FILE : newer way to restore a file
- .gitignore: file of patterns for which files/folders to ignore
- .git keep: convention to put a file in an empty folder we want

- ssh-keygen: create a ssh key
  - copy the ~/ .ssh/id_rsa.pub to your git account
  - use ssh url not https url
 - git remote add <NAME> <URL> : create remote connection
- git push REMOTE BRANCH: git push origin main (master)
-get pull REMOTE BRANCH: pull code from remote
