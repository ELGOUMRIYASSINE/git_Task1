git clone https://github.com/ELGOUMRIYASSINE/git_Task1.git 
cd Devops_task1
git checkout -b master
mkdir Task1
cd Task1
touch README.md 
cd ..
git add Task1 
git commit -m "add task1 folder and README.md file to the master branch"
git push origin master
git checkout -b "dev"
touch test.file 
git add test.file 
git commit -m "add test file to the dev branch"
git push origin dev
git checkout -b %USERNAME-new_feature
touch README.md 
git add README.md
git status
echo ".*" > .gitignore
git add .gitignore
git commit -m "add README.md file and .gitignore to %USERNAME-new_feature branch"
git add push origin %USERNAME-new_feature
git checkout dev 
git merge %USERNAME-new_feature
git push origin dev 
git checkout master 
git merge dev
git push origin master 
git checkout %USERNAME-new_feature
echo "changes" > README.md 
git commit -m "make changes to README.md file in %USERNAME-new_feature branch"
git revert HEAD
git checkout master 
git log > log.txt 
git add log.txt 
git commit -m "add log.txt"
git push origin master
git branch -D %USERNAME-new_feature
git push origin --delete %USERNAME-new_feature


