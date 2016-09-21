1.create a new repository on the command line
echo "# andriodDev" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/blowerone/andriodDev.git
git push -u origin master

2.push an existing repository from the command line
git remote add origin https://github.com/blowerone/andriodDev.git
git push -u origin master

3.删除本地仓库和远程仓库中的文件
git rm -r --cached some-directory
git commit -m 'Remove the now ignored directory "some-directory"'
git push origin master

