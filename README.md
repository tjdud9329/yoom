mkdir -p ~/github-essentials
cd $_
echo "# github essentials">>README.md
git init
git add README.md
git commit -m "first commit"
git remote add origingit@github.com:<username>/<repository>.git
git push -u origin master
