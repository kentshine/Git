# Git
<h1> Hello</h1>
### Git Version
```
-v
--version
```
### Default Value
```
git config --global user.name "NAME"
git config --global user.email "EMAIL ID"
```
### Local Branching
```
git init
```
### Git Add
```
git add <filename>
```
- To track all the files
```
git add <filename> .
```
### Git Remove
- The Git rm –cached flag removes a file from the staging area.
```
git rm --cached <filename>
```
### Git Log
- Current log (author,mail,date)
- Previous commit

```
git log
```
### Git Commit
- Issue Tracking
```
git commit -m <msg>
```
### Git Status
```
git status
```
### Checksum
- check the first 7 char.
```
[main (root-commit) fd914d5]
```
### Modified Stage
Working Dir. ----> Staging area ----> Local commit

```
git add <file name>
```
### Git Tag
- Tags are ref's that point to specific points in Git history.
```
git tag
```
- Annotated Tag
```
git tag -a v1.0 -m "<msg>"
```
- Lightweight Tag
```
git tag v1.4-lw
```
### Tag Push
- To push the tag
```
git push origin v1.0
```
### Branch
- Create branch
```
git checkout -b <branch name>
```
- List the branch
```
git branch
```
- Switch to an existing branch in Git
```
git checkout <branch name>
```
- Switch to previous branch
```
git switch -
```
- Delete the branch
```
git branch -d <branch name>
```
- To push branch to Git repo.
```
git push origin <branch name>
```
- Merging with the main branch
```
git merge <branch name>
```
