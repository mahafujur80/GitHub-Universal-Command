# GitHub-Universal-Command

# First Time Add Your REPO In Your VS Code.


git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/usename/YourRepoName.git

git push -u origin main

# Update Code In REPO by this command

git add .

git commit -m "update"

git push -u origin main




# main ব্রাঞ্চের কোড gh-pages এ merge

git checkout gh-pages

git fetch origin

git checkout -b gh-pages origin/gh-pages

git merge main

git push origin gh-pages




#  লোকাল ফোল্ডারকে GitHub repo’র সাথে connect করার জন্য


git init  

git branch -M main  

git remote add origin https://github.com/mahafujur80/MAHAFUJUR-R-MUNNA.git  

git pull origin main --rebase  

git add .  

git commit -m "First commit from local folder"  

git push -u origin main








