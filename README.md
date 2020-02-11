# Git and github introduction

This repository gives a short introduction for Fontys Venlo Software Engineering and Business Informatics students regarding usage of Git and Github. 

## What is Git?

* **DVCS** – Distributed Version Control System
* Like a **“more advanced”** SVN (Subversion)
* Most used VCS in the world (>70%)
* Used often in open source projects

## What is Github?

* Git hosting repository - [see Github.com](https://www.github.com)
* Besides hosting additional features
* Own workflow (pull requests) 
* There are more hosters: [bitbucket](https://www.bitbucket.org), [gitlab](https://www.gitlab.com) ...

More information: [github guide](https://guides.github.com/introduction/git-handbook/)

## Git basic commands

Command | Description | SVN command
--------|-------------|-------------
git clone | Clones a repository – making a local copy | svn checkout 
git status | To check the status of files you’ve changed in your working | svn status
git add | adds changes to stage/index in your working directory | svn add 
git commit  | commits your changes and sets it to new commit object for your remote | svn commit (differs in git)
git push/pull | Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes | svn commit (push is committing)
git branch | Lists out all the branches | svn copy 
git checkout |Switch to different branches | svn switch (on branches) or svn revert (on files)
git stash | Save changes that you don’t want to commit immediately | does not exist in svn
git merge | Merge two branches you were working on | svn merge
git reset  | You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with. | svn revert (differs in git) 
