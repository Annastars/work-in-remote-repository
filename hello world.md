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

чаще делать git status

## начало работы в репозитории

git init

* создает локальный репозиторий

если не ввели имя пользователя, то

git config --global user.name

git config --global user.email

## добавление фйлов в репозиторий

git add file_name

добавляет file_name  для отслеживания

git commit -m "comment"

фиксирует все команды, которые были добавлены для отслеживания

## отслеживание состояния репозитория

git status

 показывает изменненые файлы и файлы готовые для commit

git log

показвает все commit 

git diff

показывает разницу между текущей версией и зафиксированной 

## переход между commit

git checkout commit_code

переходит к commit с кодом commit_code(его можно подсмтреть по git log)

git checkout master

вернуться к актуальному состоянию
![error](funny.jpg)

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