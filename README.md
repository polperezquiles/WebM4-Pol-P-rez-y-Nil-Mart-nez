git add .
git commit -m "Reactivando GitHub Pages"
git push origin <nombre-de-la-rama>

git branch -m gh-pages <BRANCH>
git fetch origin
git branch -u origin/<BRANCH> <BRANCH>
git remote set-head origin -a
