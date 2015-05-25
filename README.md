# Min Hoo Lee's Website

[![Join the chat at https://gitter.im/minhoolee/minhoolee.github.io](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/minhoolee/minhoolee.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
This repository holds the config files I used to locally host my website using **Brackets** and **Jekyll**.  
I can host using **Github Pages** as well at [minhoolee.github.io](minhoolee.github.io).
I also redirected the github.io domain to [minhoolee.paperplane.io](minhoolee.paperplane.io).

## How to run using Jekyll
> jekyll build _--watch_  
jekyll serve

## How to make a repository and push it upstream
#### _Italics_ means optional.
#### Described in links [Stackoverflow Thread A](http://stackoverflow.com/questions/1960799/using-git-and-dropbox-together-effectively) and  [Stackoverflow Thread B](http://stackoverflow.com/questions/19312622/git-push-vs-git-push-origin-branchname):
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
