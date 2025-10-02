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



#  লোকাল ফোল্ডারকে GitHub repo’র সাথে connect করার জন্য

# 1 লোকাল রিপো তৈরি
git init  

# 2. ডিফল্ট ব্রাঞ্চকে main করা
git branch -M main  

# 3. রিমোট রিপো লিংক করা
git remote add origin https://github.com/mahafujur80/MAHAFUJUR-R-MUNNA.git  

# 4. আগে যদি GitHub এ কোড থাকে তবে সেটা লোকালে আনতে হবে (conflict এড়ানোর জন্য rebase দেওয়া যায়)
git pull origin main --rebase  

# 5. লোকাল ফাইল ট্র্যাক করা
git add .  

# 6. কমিট তৈরি করা
git commit -m "First commit from local folder"  

# 7. রিমোটে push করা
git push -u origin main  




