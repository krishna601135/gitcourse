Exploring git and github
git log --pretty=oneline --> show the all commits with one line

git branch  

creating new branch -> git checkout -b <branchName>

list of branches -> git branch,  git branch --all

the branch which is in blue color will be the active branch

switching between branches:

git checkout <branchName>

git switch <branchName>

git push origin <branchName>

conflicts


shortcut to switch between the branches
git switch -
the above is for switch between the previous branch
or
git switch -b <branchname>


Merging feature branch with main branch:

first we need checkout to the main branch

git merge

making pull request