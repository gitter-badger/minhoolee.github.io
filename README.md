# Min Hoo Lee's Website
This repository holds the config files (able to be run by jekyll as well) in order to locally host my website.  
I can host using Github Pages as well.

## How to run using Jekyll
> jekyll build _--watch_
jekyll serve

## How to make a repository and push it upstream
#### _Italics_ means optional. Described in links [A](http://stackoverflow.com/questions/1960799/using-git-and-dropbox-together-effectively) and [B](http://stackoverflow.com/questions/19312622/git-push-vs-git-push-origin-branchname):
> git init  
git add .  
git commit -m "commit text"  
git remote add origin _remote repository url_  
_git remote -v_  
git push -u origin master

#### Described from [Github](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/): 
> _echo "# Git-Test-2" >> README.md_  
git init  
git add _README.md_  
git commit -m "first commit"  
git remote add origin _https://github.com/minhoolee/Git-Test-2.git_  
git push -u origin master
