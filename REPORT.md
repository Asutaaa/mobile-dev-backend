## Bezzubnceva Anastasia M33041
![Image alt](https://github.com/Asutaaa/mobile-dev-backend/blob/report/docs/Task%201.jpg)
### Task - 2
git checkout ci
git rebase -i HEAD~9
git checkout master
git cherry-pick ci
git branch -D ci
![Image alt](https://github.com/Asutaaa/mobile-dev-backend/blob/report/docs/Task%202.png)
### Task - 3
git reflog
git checkout aca3abb
git branch old-master

### Task - 4
git blame prisma/seed.ts
![Image alt](https://github.com/Asutaaa/mobile-dev-backend/blob/report/docs/Task%204.png)
### Task - 5
git checkout master
git bisect start
git bisect bad
git bisect good
npm run test
![Image alt](https://github.com/Asutaaa/mobile-dev-backend/blob/report/docs/Task%205.jpg)
### Task - 6
git filter-branch --tree-filter "rm -f .env" -- --all
echo .env >> .gitignore

### Task - 7
git checkout feature
git filter-branch --env-filter "GIT_AUTHOR_NAME='Bezzubnceva Anastasia'; GIT_AUTHOR_EMAIL='adkam02@mail.ru'; GIT_COMMITTER_NAME='Bezzubnceva Anastasia'; GIT_COMMITTER_EMAIL='adkam02@mail.ru'" HEAD~12..HEAD
![Image alt](https://github.com/Asutaaa/mobile-dev-backend/blob/report/docs/Task%207.png)
### Task - 8
git checkout master
git config rerere.enabled true
git merge feature
git add README.md
git commit --no-edit
git reset --hard HEAD~1
git merge feature

###T ask - 9
git fsck

### Task - 10
git gc --prune=now --aggressive

### Task - 11
git add -p e
