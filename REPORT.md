##Bezzubnceva Anastasia M33041

###Task - 2
git checkout ci
git rebase -i HEAD~9
git checkout master
git cherry-pick ci
git branch -D ci

###Task - 3
git reflog
git checkout aca3abb
git branch old-master
