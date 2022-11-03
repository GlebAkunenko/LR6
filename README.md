# LR6
Лабораторная работа №6

#### Настройка конфига командой git --global. Результаты изменений.
Рисунок №1
![](Screenshots/photo1667490129.jpeg)

#### Переход к рабочей папке
Рисунок №2
![](Screenshots/photo1667491645.jpeg)

#### Клонирование удаленного репозитория
Рисунок №3
![](Screenshots/photo1667491684.jpeg)

#### Переход в папку с репозиторием
Рисунок №4
![](Screenshots/photo1667491745.jpeg)

#### Добавление файла в GitHub'е и обновление копии
Рисунок №5
![](Screenshots/photo1667491714.jpeg)
Рисунок №6
![](Screenshots/photo1667491757.jpeg)

#### Работа с ветками
Рисунок №7
![](Screenshots/photo1667491926.jpeg)
Рисунок №8
![](Screenshots/photo1667491814.jpeg)

#### Слияние ветки branch1 и master
Рисунок №9
![](Screenshots/photo1667491997.jpeg)

#### Переход в редактор Vim. Изменение файла с помощью команды :diffoff
Рисунок №10
![](Screenshots/photo1667492016.jpeg)
Рисунок №11
![](Screenshots/photo1667492077.jpeg)

#### Результат работы в редакторе Vim
Рисунок №12
![](Screenshots/photo1667492137.jpeg)

#### Удаление ветки branch1
Рисунок №13
![](Screenshots/photo1667492189.jpeg)

#### Добавление новых файлов
Рисунок №14
![](Screenshots/photo1667492241.jpeg)
Рисунок №15
![](Screenshots/photo1667492288.jpeg)

#### Фиксация изменений в коммите
Рисунок №16
![](Screenshots/photo1667492346.jpeg)

#### Возврат изменений коммита в два шага
Рисунок №17
![](Screenshots/photo1667492382.jpeg)

#### Создание отчёта
Рисунок №18
![](Screenshots/photo1667492435.jpeg)

#### Создание отчёта в текстовом блокноте
Рисунок №19
![](Screenshots/photo1667493517.jpeg)

#### Лог коммитов в текстовом формате
Рисунок №20
![](Screenshots/photo1667493506.jpeg)

## ЛОГ КОМАНД
```
$ cd D:/'Рабочий стол'/'ЛР6'
$ git clone https://github.com/AndrewFalse/LR6.git
$ git pull
$ cd LR6
$ git pull
$ git log
$ git checkout branch1
$ git checkout master
$ git merge branch1
$ git mergetool
$ git status
$ git add .
$ git commit -m 'Act of Merging'
$ git branch -d branch1
$ git branch
$ git commit -m 'Act of Adding A Bitmap'
$ git commit -m 'Act of Adding A Text'
$ git reset --hard HEAD~2
$ git checkout -b 'Отчёт'
$ git log --pretty="%h %ad %ch"
````
####

