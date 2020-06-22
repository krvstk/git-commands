# Helpful commands for Git

###### Check remote, locally known, branches: 
`git branch -r`

###### Update the local list of remote branches:
`git remote update origin --prune`

###### Create and checkout to a new branch:
`git checkout -b 'branch-name'`

## Pull request algorithm:
0) Add some changed file or all changed files to commit:
`git add 'file.html'` or `git add *`
1) Commit changes:
`git commit -m 'message text'`
2) Actualize branch before push:
`git pull origin master'`
3) Push branch with commit to remote repository:
`git push origin branchname'`
4) Manually press 'pull request' button on remote repository page on **pushed branch**.
