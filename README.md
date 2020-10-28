# Helpful commands for Git

###### Check remote (non-fetched) and local branches: 
`git branch -r`

###### Check remote branches: 
`git branch -a`

###### Delete remote branche: 
`git push origin --delete 'branch-name'`

###### Update the local list of remote branches:
`git remote update origin --prune`

###### Create and checkout to a new branch:
`git checkout -b 'branch-name'`

## Pull request algorithm:

0) Add some changed file or all changed files to commit:  
`git add 'file.html'`  
or  
`git add *`
1) Commit changes:  
`git commit -m 'message text'`
2) Actualize branch before push:  
`git pull origin master`
3) Push branch with commit to remote repository:  
`git push origin branchname`
4) Manually press 'pull request' button on remote repository page on **pushed branch**.


###### List conflicted files:  
`git diff --name-only --diff-filter=U`

###### Stash file:
`git stash push 'file.html'`
