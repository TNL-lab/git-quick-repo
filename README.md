\#create new folder

mkdir new-folder-project

\## change directory to new folder

cd new-folder-project

\##initalize git repo

git init

\##Add first commit

git add README.md

git commit -m "inital commit"

\##create new main branch

git branch -M main

\##login Github

gh auth login

//create git repo on remote

gh repo create my-project --public --source=. --remote=origin

\##push code 

git push -u origin main

