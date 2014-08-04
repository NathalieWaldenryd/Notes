The Data Scientist's Toolbox
============================

 

##Git Bash

pwd                    print working directory

clear                    clear all

ls                          list what's in directory

ls –a                    list all, including hidden files

cd                         change directory

cd..                      move up one directory

mkdir                  make a new directory

touch                  create an empty file

cp                         copy  <filename> <directory>

cp –r                    moves one directory into another

rm                        remove files

rm –r                  remove directory

mv                       move file to a different directory (can also be used to rename)

echo                    prints arguments

date                    today's date and time

exit                      exit

 

##Git

git add.               adds all new files

git add –u           updates tracking

git add –A          does both of the above

git commit –m "message"          commits repo

git push              pushes files to Github

git checkout –b <branchame>  checks out repo

git branch          creates a branch

git checkout master       checks out master repo

*                           wildcard

<tab>                  autocomplete

<up arrow>        copy from above

 

##Markdown language

.md                     suffix used for markdown files

#                           secondary heading

##                        tertiary heading

*                          bullet pointed item

 

Stack Overflow

Good help resource

 

##Moving files to Github

$ git add *.md

$ git commit –m "description here"

$ git remote add origin https://github.com/<your github username>/<project name>.git

$ git push –u origin master

 

##Making new directories

$ mkdir ~/test-repo

$ cd ~/test-repo

$ git init

$ git remote add origin http://github.com/<your github username>/test-repo.git

 

Forking

$ git clone http://github.com/<your github username>/<reponame>.git

Credit:Barbara Dirsa
