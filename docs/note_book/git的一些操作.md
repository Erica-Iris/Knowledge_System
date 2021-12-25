Git 全局设置:

git config --global user.name "Neo Iris"
git config --global user.email "ediath462@gmail.com"
创建 git 仓库:

mkdir diary
cd diary
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://gitee.com/ediath-wu/diary.git
git push -u origin master
已有仓库?

cd existing_git_repo
git remote add origin https://gitee.com/ediath-wu/diary.git
git push -u origin master