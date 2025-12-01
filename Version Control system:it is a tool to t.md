#Day1

Version Control system:it is a tool to track the snapshot of the file/project.
Git??
Installed the Github
Created an account in Github
Created a repository in github account


#Day2

->Code for the First Time 
git config --global user.name "shailendraDev7"
git config --global user.email "shailendrastha7@gmail.com"

git remote add origin https://github.com/shailendraDev7/projectgit.git



Golden Circle: Most of the time we'll use these commandlines of git for the project.

git init
git add .
git commit -m "Commit Message" || Staged
git push -u origin main

[Commits: A simple snapshots/state of the project]


#Day3

- Updating the repository
- Adding the file and updating
- Branches?? Tree ->main, AboutFeature, AboutFeatureBugFix 
    - Branch Creation
    - Switching the branches
    - Renaming the branches
    - Pushing the branches to the repository
    - Individual branch concepts


git branch <branch-name> : it copies the entire files of the original branch
git checkout <branch-name> : To switch to the another branch

git push --all origin : Pushes all to the online repository


#Day4
- git pull
- git switch -c feature/<branch-name>
- echo "<h1>Page content</h1>">file.html
-echo "body {background: green}">>style.css