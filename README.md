##ОТЧЁТ О ЛАБОРАТОРНОЙ РАБОТЕ №6 
## ПО ОСНОВАМ ПРОГРАММИРОВАНИЯ



###Ход работы:
На сайте GitHub сделал копию https://github.com/Kurtyanik/LR6/
![Копированный репозиторий](screenshots/Screenshot_1.png)
С помощью команды _cd Desktop/lab6_ в консоли Git Bash перешёл в созданную на рабочем столе папку lab6
Использовал команду _git init_ чтобы инициализировать гит в данной папке
![Git init](screenshots/Screenshot_2.png)
Командой _git remote add origin_ связал папку с удалённым репозиторием на сайте GitHub
![Git remote add origin](screenshots/Screenshot_4.png)
Затем через графический интерфейс GitHub добавил новый файл _Index.html_ в удалённый репозиторий и добавил его в ветку __master__
![Новый файл](screenshots/Screenshot_5.png)
![Нф](screenshots/Screenshot_6.png)
![Нф](screenshots/Screenshot_7.png)
![Nf](screenshots/Screenshot_8.png)
Пользуясь командой _git pull origin master_ загрузил изменения из удалённого репозитория в локальный
![Git pull](screenshots/Screenshot_9.png)
Командой _git log_ получил список операций/коммитов
![git log](screenshots/Screenshot_10.png)
Используя _git show *commit SHA-1*_ получил более подробную информацию по последнему изменению
![git show](screenshots/Screenshot_11.png)
Командой _git checkout -t branch1_ переключился на другую ветку **branch1**
![git checkout](screenshots/Screenshot_12.png)
Попытался выполнить слияние веток **master** и **branch1** командой _git merge branch1_ и получил ошибку
![Merge error](screenshots/Screenshot_13.png)
Вручную изменил файл mergefile.txt, вызвавший ошибку слияния и выполнил коммит
![Fix](screenshots/Screenshot_14.png)
Выполнил слияние веток **master** и **branch1** а затем удалил ветку **branch1** командой _it
![Merge](screenshots/Screenshot_15.png)
![Branch delete](screenshots/Screenshot_16.png)
Запушил всё в удалённый репозиторий командой _git push origin master_ (Строка logon failed вылезает из-за какой-то внутренней ошибки)
![Push1](screenshots/Screenshot_17.png)
Затем сделал несколько изменений, добавив новые файлы
![New files](screenshots/Screenshot_19.png)
![New files git](screenshots/Screenshot_20.png)
Командой _git reset --hard HEAD~1_ выполнил откат последнего коммита - добавления файла **Новый текстовый документ.txt**
![Hard reset](screenshots/Screenshot_22.png)
Запушил изменённую ветку
![Push2](screenshots/Screenshot_23.png)
![Push2 result](screenshots/Screenshot_24.png)
Пользуясь командой _git checkout -b otchet_ создал новую ветку **otchet**
![New branch](screenshots/Screenshot_25.png)
Текущая история _git log --graph_ . Аргумент --graph позволяет графически изобразить ветки и коммиты на них
![Git log2](screenshots/Screenshot_26.png)
С помощью команды _git add ._ подготовил все новые файлы в папке **lab6** к пушу
![Git add .](screenshots/Screenshot_28.png)
Запушил файлы скриншотов в удалённый репозиторий
![Git add .](screenshots/Screenshot_29.png)
Оформляю отчёт в файле **README.md** используя блокнот
![Readme](screenshots/Screenshot_31.png)


Лог команд из папки **.git/logs**
![Logs](screenshots/Screenshot_30.png)
Финальный результат команды _git log_
![Git log3](screenshots/Screenshot_32.png)
Все файлы скриншотов лежат в папке **screenshots**