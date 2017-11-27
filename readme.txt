Git is a distirbuted version control system
Git is free software distributed under the GPL
hello ,Git
Git has a mutable index called stage

git init
git add filename
git commit -m "  "
git status
git diff filename
git diff HEAD --filename
git log
git reflog
git reset --hard HEAD^ or HEAD~100
git reset --hard commit_ID
git checkout -- filename   git reset HEAD filename
git rm -- filename

shh-keygen -t rsa -C "32092288@qq.com"

git remote add origin https://github.com/32092288/githubtest.git  //https need to input username & password

git push -u origin master
git push origin master

git clone git@github.com:32092288/gitskills.git   //ssh no need to input username & password

git checkout -b dev  //step:1 git branch dev 2 git checkout dev 3 switch to branch 'dev'

git branch   //view current branch, list all branch , current branch with '*'


git checkout master
git checkout dev

git merge dev

git branch -d dev

creating a new branch is quick AND simple

