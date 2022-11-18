# Лабораторная работа №6
## Акуненко Глеб 4117

Перед работой с репозиторием произведена настойка git config.

<img src="Images/1.png" width="700">

В GitHub создан форк репозитория https://github.com/Kurtyanik/LR6. В git создана локальная копия удалённого репозитория.

<img src="Images/2.png" width="700">

В удалённом репозитории создан новый файл.

<img src="Images/1.2.png" width="700">

С помощью команды `git pull` изменения в удалённом репозитории загружены в локальный репозиторий.

<img src="Images/3.png" width="700">

С помощью команды `git log` получены последние изменения репозитория.

<img src="Images/4.png" width="700">

С помощью команды `git checkout branch1` 
загрузим из удалённого репозитория ветку *branch1* и 
перейдём на неё. Перейдя на ветку *master* проведём слияние этой ветки
с *branch1* с помощью команды `git merge branch1`. С помощью
`git status` ПРИВЕТ ХАБР можно увидеть конфликт.

<img src="Images/5.png" width="700">

Конфликт слияния решается командой `git checkout mergefile.txt --ours`,
которая использует версию файла ветки *master*.

<img src="Images/6.png" width="700">

Команда `git branch -d branch1` удаляет ненужную ветку 
*branch1*. 

<img src="Images/7.png" width="700">

Используя команду `git add` можно добавить файлы в индекс.
Команда `git commit -m"<комментарий>"`, создаёт коммит из
файлов находящихся в индексе.

<img src="Images/8.png" width="700">

Команда `git reset --hard <ветка>` выполняет откат до ветки,
удаляя все вышестоящие.

<img src="Images/9.png" width="700">

Ключ `--pretty` позволяет настроить формат вывода команды
`git log`

<img src="Images/10.png" width="700">

Лог команд:
```
git config --global user.name "Gleb Akunenko"
git config --global user.email "akunenko.study@gmail.com"
git clone https://github.com/GlebAkunenko/LR6.git
git pull
git log
git checkout branch1
git checkout master
git merge branch1
git status
git checkout .\mergefile.txt --ours
git status
git add *
git commit -m"Commit after merge"
git branch
git branch -d branch1
git branch
git status
git add .
git status
git commit -m "Wrong commit"
git log --pretty=oneline -3
git reset --hard HEAD~1
git log --pretty=oneline -3
```
