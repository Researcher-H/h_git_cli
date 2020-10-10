# Gitの基本

- https://backlog.com/ja/git-tutorial/intro/01/  
- https://hacknote.jp/archives/54105/  
- https://www.a2hosting.co.uk/kb/developer-corner/version-control-systems1/403-forbidden-error-message-when-you-try-to-push-to-a-github-repository  
- https://stackoverflow.com/questions/35942754/how-to-save-username-and-password-in-git-gitextension  
- https://zenn.dev/alex/articles/1a0baa652954bfdbe4f6

git config --global user.name "username"
git config --global user.email useremail
git remote set-url origin remote repository

git fetch // avoid conflict with other users

git flow <- when collaborating with a team
github flow 
gitlab-flow

- master
- .
- .
- .
- develop -- remain
- feature -- remove after use

git checkout -b develop
git checkout -b feature/add_html_file

fork flow <- when so many collaborators

git push --set-upstream origin develop

git branch develop 
git checkout develop 
git push --set-upstream origin develop 

git status
git diff README.md

git fetch

git branch -a
git config --global credential.helper store
git pull
git checkout -b develop
git branch -a
git status
git checkout -b feature/add_html_file
git branch -a
git checkout develop
git branch -a
git add README.md
git commit -m develop "branch"
git push --set-upstream origin develop
