readme
git config --global user.name "Alex"
git config --global user.email "908588464@qq.com"
git init

echo aa > readme.txt
git add readme.txt

git commit -m "commit readme.txt"
git status
git diff
git clone https://github.com/AlexLoveXin/Garbage.git
git push -u origin master
git remote add origin https://github.com/AlexLoveXin/Garbage.git
