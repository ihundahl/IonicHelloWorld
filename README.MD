## Hello World on Ionic 2 Framework

### Setup

`npm install -g ionic cordova`

`git remote add origin https://github.com/ihundahl/IonicHelloWorld.git`

`git remote -v`

`git pull origin master`

### Create branch

`git checkout -b someBranchName` 

Edit/personalize home.page.html

`git add .`

`git commit -m "personalized hello world"`

`git fetch`

`git rebase -i origin/master`

`git checkout master && git pull`

`git merge someBranchName && git push`

`git branch -d someBranchName`

### To Run

`ionic serve`
