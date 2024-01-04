# Git 

- git a version control system or tool. simply, a system to manage your files.
- Saves the file locally or remote server(github/gitlab)
- Made by the linux development community

### Method #1

~~~
pc@DESKTOP-I5GUQBR MINGW64 ~
$ cd Desktop/

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop
$ mkdir gtst && cd gtst

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst
$ git init
Initialized empty Git repository in C:/Users/pc/Desktop/gtst/.git/

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git config --global user.name faruq

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git config --global user.emil faruqasrar.com@gmail.com

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git status
On branch faruq

No commits yet

nothing to commit (create/copy files and use "git add" to track)

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git status
On branch faruq

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        day1.md

nothing added to commit but untracked files present (use "git add" to track)

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git add .

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git commit -m 'First time commit'
[faruq (root-commit) be91e98] First time commit
 1 file changed, 1 insertion(+)
 create mode 100644 day1.md

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git status
On branch faruq
nothing to commit, working tree clean

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$ git log
commit be91e98003fdc83a9453724faa4230a73be39c2f (HEAD -> faruq)
Author: faruq <faruqasrar.com@gmail.com>
Date:   Wed Jan 3 04:20:24 2024 -0800

    First time commit

pc@DESKTOP-I5GUQBR MINGW64 ~/Desktop/gtst (faruq)
$
~~~


## GitHub

- GitHub is a Wed site/server which your git is hosted on.
- You files will be saved in folder called "**REPOSITORY**". 
### obsidian



#### Visual Studio Code






