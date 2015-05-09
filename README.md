# Min Hoo Lee's Website
This repository holds the config files I used to locally host my website using **Brackets** and **Jekyll**.  
I can host using **Github Pages** as well at _minhoolee.github.io_.

## How to run using Jekyll
> jekyll build _--watch_  
jekyll serve

## How to make a repository and push it upstream
#### _Italics_ means optional.
#### Described in links [Stackoverflow Thread A](http://stackoverflow.com/questions/1960799/using-git-and-dropbox-together-effectively)
#### and  [Stackoverflow Thread B](http://stackoverflow.com/questions/19312622/git-push-vs-git-push-origin-branchname):
> git init  
git add .  
git commit -m "commit text"  
git remote add origin _remote repository url_  
_git remote -v_  
git push -u origin master

#### Described in [Github Help Article](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/): 
> _echo "# Git-Test-2" >> README.md_  
git init  
git add _README.md_  
git commit -m "first commit"  
git remote add origin _https://github.com/minhoolee/Git-Test-2.git_  
git push -u origin master

#### Github commands as described in [Github Command Sheet](https://github.com/WebDevStudios/CLI-Cheat-Sheet/blob/master/git-commands.md):
