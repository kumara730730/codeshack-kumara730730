git config --global user.name "kumara730730"

git config --global user.email "kumara730730@gmail.com"

git config --global --list 

Output:
user.name=kumara730730
user.email=kumara730730@gmail.com
safe.directory=*

gh auth login

gh auth status
Login active to this account

gh repo create codeshack-kumara730730 --public --clone

cd codeshack-kumara730730
code README.md
code git-notes.md

Made changes to README.md and git-notes

git add git-notes.md
git add README.md
git status
git diff
git log --oneline

Rename-item gitnotes.md git-notes.md

git branch -m main
git branch

git commit -m "message"
git push -u origin main
git remote -v

git pull 
git fetch