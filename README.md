<div align="center">
  <img src="git.png" alt="Logo" width="100" height="100" style="display:block; margin:auto;">
  <p>There are many different ways to use Git. Git supports many command-line tools and graphical user interfaces. The Git command line is the only place where you can run all the Git commands.<p>
</div>

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
> To track all the files
```
git add <filename> .
```
### Git Remove
> The Git rm –cached flag removes a file from the staging area.
```
git rm --cached <filename>
```
> Undo git rm 
```
git reset
```
### Git Log
- Current log (author,mail,date)
> Previous commit

```
git log
```
> To see a very compressed log where each commit is one line:
```
git log --pretty=oneline
```
> See only which files have changed:
```
git log --name-status
```
### Git Commit
- Issue Tracking
```
git commit -m <msg>
```
### Git Revert
- Reverts a commit
```
git revert HEAD
```
### Git Status
> Checking the Status of Your Files
```
git status
```
> Short Status
```
git status -s
```
### File Moving
> mv
```
git mv file_from file_to
```
### Checksum
> check the first 7 char.
```
[main (root-commit) fd914d5]
```
### Modified Stage
Working Dir. ----> Staging area ----> Local commit

```
git add <file name>
```
### Git Tag
> Tags are ref's that point to specific points in Git history.
```
git tag
```
> Delete Tag
```
git tag -d v1.0
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
> To push the tag
```
git push origin v1.0
```
### Branch
> Create branch:
```
git checkout -b <branch name>
```
> List the branch:
```
git branch
```
> Switch to an existing branch in Git:
```
git checkout <branch name>
```
> Switch to previous branch:
```
git switch -
```
> Delete the branch:
```
git branch -d <branch name>
```
> To push branch to Git repo.:
```
git push origin <branch name>
```
> Merging with the main branch:
```
git merge <branch name>
```
### Git Aliases
- Creating shortcuts' for Git commands
> eg:  Instead of typing git commit, you just need to type git ci.
```
 git config --global alias.br branch
 git config --global alias.ci commit
 git config --global alias.st status
```
