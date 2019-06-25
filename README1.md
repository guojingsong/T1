git config --global user.name "guojingsong"
git config --global user.email "13501112460@163.com"
git config -l

git add docker_memo.txt
git commit -m "aaa"


git remote rm  origin
git remote add origin https://github.com/guojingsong/T1.git
git remote -v
git push -u origin master


