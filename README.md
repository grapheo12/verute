# VeRuTE
VeRuTE is a static site generator built using NodeJS.

VeRuTE stands for Very Rudimentary Template Engine.

Proposed capabilities:
```
verute init    #Make a directory structure with git repo

verute gensites    #Look in data folder for markdown files. Go to designated templates in those files and fill
                   #the templates with the given data. Then save it to the designated directory.
                   #data folder will have _tracking.json which will markdown files that have been taken care of
                   
verute deploy      #Make deploy branch up to date with current branch. Then push the deploy branch to remote server
```
Also, it will have a live creator where you can see your site getting built live as you type your markdown.

