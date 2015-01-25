# courses
Submissions for courses

Newbie info on setting up Git Bash

On Git Bash (once):
git config --global user.name "NJBongithub"
git config --global user.email "NJBongithub@gmail.com"
git config --list
exit

Newbie info on linking a local folder to GitHub repo

On Git Bash (once):
mkdir ~/datasciencecoursera
cd ~/datasciencecoursera
git init
git remote set-url --add origin https://github.com/NJBongithub/courses.git

Newbie info on sync'ing changes as you go

On Git Bash (as needed):
cd ~/datasciencecoursera
git add -A
git commit -m "message must be entered"
git push
