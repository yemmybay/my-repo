echo "# my-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M production
git remote add origin git@github.com:yemmybay/my-repo.git
git push -u origin production
