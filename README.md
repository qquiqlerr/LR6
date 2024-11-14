# LR6
Лабораторная работа №6

![img.png](screenshots/img.png)просмотр истории операций командой `git log`

![img_1.png](screenshots/img_1.png)работа с README.md в JetBrains IDE

![img.png](screenshots/img3.png)окно работы с git в JetBrains IDE

![img.png](screenshots/img_5.png) reflog

![img_1.png](screenshots/img_4.png)

# Последовательность действий
1. Клонировал GitHub репозиторий используя
```bash
git clone https://github.com/qquiqlerr/LR6
```


2. Просмотрел логи всех веток
```bash
git branch
git log branch1
git log master
```


3. Смержил ветку branch1 в master используя средства IDE для разрешения конфликтов


4. Удалил branch1 с помощью
```bash
git branch -d branch1
```

5. Сделал несколько коммитов, оставляя логичные и понятные комментарии
6. Удалил последний коммит с помощью
```bash
git reset HEAD~
```

7. Создал новую ветку для отчета


8. Удалил отчет с мастера и залил в отдельную ветку