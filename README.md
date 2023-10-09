### Git Add Remote
```vim
$git remote add origin git@github.com:User/UserRepo.git
$git config --global user.email <email>
$git config --global user.name <name>
```
### Git Show Remote Info
```vim
$git remote show origin
```
### Git Clone
```vim
//Branch
$git clone -b <branch-name> <git-repository-url>
//Master
$git clone <git-repository-url>
```
### Git Pull/Add/Commit/Tag/Push
```vim
$git pull origin <branch_name>
$git add .
$git commit -m 'My Message'
$git tag <tag_name>
$git push origin <branch-name>
```
### Git Push Tags
```vim
//Tags should be only added per latest commit
$git push origin --tags
//Delete local tag
$git tag --delete tagname
//Delete remote tag
$git push --delete origin tagname
```
### Git Checkout
```vim
$git clone <git-repository-url>
//Select your prefered branch
$git checkout <branch name>
```
### Delete All Commit before HEAD / Delete all commit
```vim
$git reset --hard HEAD~1
```
### Reset specific commit
```vim
$git reset --hard <commit-id>
```
### Git Log
```vim
//check list of commits
$git log
```
### Remove a remote branch in Git
```vim
$git push --delete origin branch_name_here
```
### Use Git rebase
```vim
You can transfer completed work from one branch to another using git rebase
$git checkout master_branch
$git rebase branch_name_here
```
### Create Branch and Switch to it
```vim
$git checkout -b branch_name
```
### Switch to newly created Branch
```vim
$git checkout branch_name
```

### Create Branch
```vim
$git branch branch_name
```
### Git Merge
```vim
https://www.freecodecamp.org/news/git-undo-merge-how-to-revert-the-last-merge-commit-in-git/
```
### References
[GIT CHEAT SHEET](https://www.freecodecamp.org/news/git-cheat-sheet/)
### Cheat Sheet
<img src="git-cheat-sheet.jpg"></img>
