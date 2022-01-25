# first heading for the version control 

## highlightning text

 *italics.*

 **bold**

## lists

 * element 1

 * element 2

 * element 3

 1. 1 num element

 2. 2 num element

 3. 3 num element

# Инструкция по работе с GIT

![error](funny.jpg)

## начало работы в репозитории

**git init**

* создает локальный репозиторий

если не ввели имя пользователя, то

git config --global user.name

git config --global user.email

## добавление фйлов в репозиторий

**git add file_name**

добавляет file_name  для отслеживания

**git commit -m "comment"**

фиксирует все команды, которые были добавлены для отслеживания

## отслеживание состояния репозитория

**git status**

 показывает изменненые файлы и файлы готовые для commit

**git log**

для визуализации веток, добавляйте тег:

git log --graph

показвает все commit 

**git diff**

показывает разницу между текущей версией и зафиксированной 

## переход между commit

**git checkout commit_code**

переходит к commit с кодом commit_code(его можно подсмтреть по git log)

**git checkout master**

вернуться к актуальному состоянию

## branch info

* to see all branches 

**git branch**

* to make a new 

**git branch branch_name**

* to change the branch 

**git checkout branch_name**

## merging branches and resolving conflicts

* to download information from the branch_name branch to the current branch

**git merge branch_name**

* to solve the merge conflict, you need to remove the extra lines and edit the text.

**delete**

## help

* to call help for a command, you need to add the tag:

**--help**

examples:

git add --help

git commit --help

git branch --help

## work in the remote repository (Github)

1. create an account in **GITHUB.COM**

* you can use any name you want

2. make a new repository

* give it a name 

3. make a connection between local and remote repository

* git remote add origin (link)

* git branch -M main

* git push -u origin main

4. send (**PUSH**) information from the local to remote repository

5. edit file from another computer

6. download (**PULL**) the current state from the remote repository

7. to start working in file from the remote repository

* **git clone (the link)**

8. **git remote**

9. **cd**

10. **PULL REQUEST**
