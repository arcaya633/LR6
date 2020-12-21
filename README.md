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

