reate a new repository on the command line
 echo "# gittemplete" >> README.md
 ```
 git config --global user.name "qssq"
  git config --global user.email "qssq666@foxmai.com"
git init
git add README.md
git add -A #ADD ALL
git commit -m "first commit"
git remote add origin https://github.com/qssq/gittemplete.git
git push -u origin master

git tag v1.0 创建v1.0标签
git remote add origin https://github.com/qssq/linuxcpp.git
git remote add origin https://github.com/qssq/cmaketest.git

git show v1.0查看指定标签的记录
git log --pretty=oneline --abbrev-commit


git merge dev 把dev分支合并到当前分支.
 git merge --no-ff -m "merge with no-ff" dev 合并分支但是不删除提交记录
git branch -d dev 删除dev分支
git branch -D <name>删除一个分支不存档
查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
```
or push an existing repository from the command line

sudo apt-get install gitg
sudo apt-get install gitk
sudo apt-get install git-cola
gitkraken
sudo apt-get install giggle
https://www.gitkraken.com/download/linux-deb
sudo dpkg -i gitkraken-amd64.deb
```
git remote add origin https://github.com/qssq/gittemplete.git
git push -u origin master
git check-ignore
git pull
git pull origin master
 git add -f App.class 强制提交被忽略的文件
 git check-ignore -v .idea 查看忽略记录
git reflog
git remote -v

# Windows:
Thumbs.db
ehthumbs.db
Desktop.ini

# Python:
*.py[cod]
*.so
*.egg
*.egg-info
dist
build

# My configurations:
db.ini
deploy_key_rsa


```
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

 git reset --hard HEAD~
git ignore file templete 
.gitignore场景1：当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令git checkout -- file。

场景2：当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令git reset HEAD <file>，就回到了场景1，第二步按场景1操作。

场景3：已经提交了不合适的修改到版本库时，想要撤销本次提交，参考版本回退一节，不过前提是没有推送到远程库。
```
/cmake-build-debug
/.idea
/*.i64
/*.out
/out
/*.h~
/*.c~
/*.cmake~
/CMakeFiles
/cmake-build-debug-cygwin
/*.cpp~

```

android studio ignorea

```
.idea
/.settings
*.iml
/.idea
/gradlew
/gradlew.bat
build
.gradle
import-summary.txt
/captures
/picture
```