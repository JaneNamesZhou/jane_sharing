## fork操作
git clone https://github.com/A/A.git
git remote add upstream ssh://git@gitlab.digitwin.com.cn:2222/twinverse-platform/twinverse-admin/twinverse-admin-api.git

git remote -v

## upstream
git add .
git status -s
git commit -m ""
git push -u origin master


## origin
git pull upstream master
git push origin


git add .
git status -s
git commit -m ""
git push -u origin master


git branch

ssh-keygen -C "jane.zhou@digitwin.com" -t rsa