# Static Site
Static site built using following stack
1. Twitter Bootsrap V3 for theme
2. JQuery for dynamic behavior
3. Google Analytics for tracking site usage
4. Linked in profile icon



## Setup
git clone git@github.com:hariinfo/static-site-template.git

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:hariinfo/static-site-template.git
git push -u origin master

## Add an existing repo to git
git remote add origin git@github.com:hariinfo/static-site-template.git
git push -u origin master

## Delete files in git repo
git filter-branch -f --tree-filter 'rm -rf *' HEAD
git push origin master --force
