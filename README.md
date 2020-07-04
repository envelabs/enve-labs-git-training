# Git

#### Get a copy of an existing project from the server for the first time
```
git clone git@<domain.cc>:<repo>
```

ex. https version

```
git clone https://github.com/envelabs/enve-labs-git-training.git
```

ex. ssh version

```
git clone git@github.com:envelabs/enve-labs-git-training.git
```

#### Check for status/changes
```
git status
```

#### Stage a file for the next local commit
```
git add <file>
```

#### Stage all files for the next local commit (don't forget the dot after the add)
```
git add .
```

#### Check in locally
```
git commit -m "<changes added>"
```

#### Push local commits to the server
```
git push
```

#### Get and merge updates from the server
```
git pull
```

#### Create a local branch
```
git branch <banch>
```

#### Create a new local branch and check it out
```
git checkout -b <branch>
```

#### Switch to a local branch
```
git checkout <branch>
```

#### Overview of local branches
```
git branch
```

#### Delete local branch
```
git branch -d <branch>
```

#### Delete remote branch
```
git push origin --delete <branch>
```

#### Switch to the previous branch (don't forget the dash after the checkout)
```
git checkout -
```

#### Insert changes on the server before your local changes
```
git pull --rebase
```

#### Temporarily discard local changes
```
git stash
```

#### Re-apply stashed away changes
```
git stash apply
```

#### Re-apply stashed away changes an delete them from stack
```
git stash pop
```

#### Find out who wrote something
```
git blame <file>`
```

#### Restore a deleted file (notice the space before and after the double dash)
```
git checkout -- filename
```

#### Clone a project
```
git clone git@github.com:envelabs/enve-labs-git-training.git
```

#### Check status (where are we?)
```
git status
```
#### Merge Procedure from 'develop' branch to 'master' branch
```
git checkout develop

git pull origin develop

git checkout master

git merge develop

git push origin master
