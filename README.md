### Git Remote
```
git remote add origin git@github.com:User/UserRepo.git
git config --global user.email <email>
git config --global user.name <name>
```
### Git Pull/Add/Commit/Tag/Push
```
git pull <branch_name>
git add .
git commit -m 'My Message'
git tag <tag_name>
git push origin <branch-name>
```
### Git Push Tags
```
//Tags should be only added per latest commit
git push origin --tags
//Delete local tag
git tag --delete tagname
//Delete remote tag
git push --delete origin tagname
```
### Git Checkout
```
//Select your prefered branch
git checkout <branch name>
```
### Git Clone
```
git clone <https://gitrepository>
```
### Delete All Commit before HEAD / Delete all commit
```
git reset --hard HEAD~1
```
### Reset specific commit
```
git reset --hard <commit-id>
```
### Git Log
```
//check list of commits
git log
```
### Remove a remote branch in Git
```
git push --delete origin branch_name_here
```
### Use Git rebase
```
You can transfer completed work from one branch to another using git rebase
$git rebase branch_name_here
```
