# YShi-test
A test.
Hi there！I am new here.

Tutorial
https://guides.github.com/activities/hello-world/

Command line instructions

Git global setup
git config --global user.name "Shi, Yongquan"
git config --global user.email "yongquan.shi@analog.com"

Create a new repository
git clone git@gitlab.analog.com:YShi/3124.git
cd 3124
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin git@gitlab.analog.com:YShi/3124.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote add origin git@gitlab.analog.com:YShi/3124.git
git push -u origin --all
git push -u origin --tags
