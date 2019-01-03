reate a new repository on the command line
 echo "# gittemplete" >> README.md
 ```
git init
git add README.md
git add -A #ADD ALL
git commit -m "first commit"
git remote add origin https://github.com/qssq/gittemplete.git
git push -u origin master
…
```
or push an existing repository from the command line
```
git remote add origin https://github.com/qssq/gittemplete.git
git push -u origin master
```
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


git ignore file templete 
.gitignore
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