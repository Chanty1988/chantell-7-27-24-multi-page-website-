echo "# chantell-7-27-24-multi-page-website-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Chanty1988/chantell-7-27-24-multi-page-website-.git
curl -sS https://webi.sh/gh | sh
gh auth login
git config user.name "Chanty1988"
git config user.email "chantellconrey322@gmail.com"
git push -u origin main
