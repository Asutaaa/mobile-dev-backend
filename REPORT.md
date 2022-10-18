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

###Task - 4
git blame prisma/seed.ts

###Task - 5
git checkout master
git bisect start
git bisect bad
git bisect good
npm run test

###Task - 6
git filter-branch --tree-filter "rm -f .env" -- --all
echo .env >> .gitignore
