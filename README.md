# LR6
Лабораторная работа №6

### Ход работы:
Зашел в репозиторий https://github.com/Kurtyanik/LR6/ и скопировал в свои репозитории
![Fork](screenshots/1.png)

Через терминал зашел в нужную директорию на диске компьютера и ввел комманду git init, связал удаленный репозиторий с папкой с помощью команды git remote add origin и клонировал на локальный репозиторий
![Git init](screenshots/2.png)

С помощью графического интерфейса на удаленном репозитории создал файл hello-world.cpp и запуллил коммит с помощью комманды git pull на локальный репозиторий
![Creating .cpp file](screenshots/4.png)
![Git pull](screenshots/3.png)

Команда git log показывает все действия в репозитории
![Git log](screenshots/5.png)

Команда git show покажет конкретные изменения по последнему коммиту
![Git show](screenshots/6.png)

Переключимся на ветку branch1 с помощью git checkout -t origin/branch1
Переключимся обратно на master и попробуем объединить ветки, но получим ошибку
![Branches](screenshots/7.png)

Исправляем конфликт в файле mergefile.txt
![Fix](screenshots/8.png)

После изменения файла добавляем его для коммита командой git add, делаем коммит и повторяем попытку, а затем удаляем branch1
![Merge](screenshots/9.png)

Производим push изменений на удаленный репозитиорий
![Push](screenshots/10.png)


Далее сделаем изменения в удаленном репозитории. Создадим три файла, один из которых окажется бесполезным:
![Remote changes](screenshots/11.png)

Обновим локальный репозиторий и посмотрим логи
![Logs](screenshots/12.png)

Откатимся до последнего коммита и запушим изменения на удаленный репозиторий
![Hard reser](screenshots/13.png)

Как видим, последний коммит был удален
![Last commit](screenshots/14.png)

Создадим новую ветку report
![New branch](screenshots/15.png)

Также мы можем посмотреть логи в графическом виде
![Graph log](screenshots/16.png)

В ветку report добавим наши скриншоты и посмотрим статус ветки, который показывает, какие изменения будут совершены следующим коммитом
![Commit screenshots](screenshots/17.png)

Делаем коммит и пушим на удаленный репозиторий
![Push commit](screenshots/18.png)
