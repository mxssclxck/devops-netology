# devops-netology
# Домашнее задание к занятию «Системы контроля версий» - Никоноров Денис - FOPS-6

## File ignored
Локальные каталоги .terraform
Файлы .tfstate
Логи сбоев
и т.д 

## Задание 1.

Создан публичный репозиторий

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/1.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/1.png)

Склонирован репозиторий, используя протокол HTTPS

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/2.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/2.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/3.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/3.png)

Перешли в каталог с клоном репозитория (cd devops-netology).

Произвели первоначальную настройку Git, указали своё настоящее фамилию и имя, и email

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/4.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/4.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/5.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/5.png)

Выполняем команду git status и запоминаем результат.

Редактируем  файл README.md, тем самым переведя файл в состояние Modified.

Ещё раз выполняем git status и продолжаем проверять вывод этой команды после каждого следующего шага.

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/6.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/6.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/7.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/7.png)

Теперь посмотрим изменения в файле README.md, выполняя команды git diff и git diff --staged.

Переводим файл в состояние staged командой git add README.md.

И ещё раз выполните команды git diff и git diff --staged. Поиграйте с изменениями и этими командами, чтобы чётко понять, что и когда они отображают.

Теперь можно сделать коммит git commit -m 'First commit'.

И ещё раз посмотреть выводы команд git status, git diff и git diff --staged.

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/8.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/8.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/9.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/9.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/10.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/10.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/11.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/11.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/12.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/12.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/13.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/13.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/14.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/14.png)

## Создание файлов .gitignore и воторого коммита

Создаем файл .gitignore

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/15.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/15.png)

Добавляем файл .gitignore в след коммит
Cоздан соотвествующий каталог terraform и внутри этого каталога — файл .gitignore по примеру: https://github.com/github/gitignore/blob/master/Terraform.gitignore.
В файле README.md опишите своими словами, какие файлы будут проигнорированы 
в будущем благодаря добавленному .gitignore.
Закоммитьте все новые и изменённые файлы. Комментарий к коммиту должен быть Added gitignore.

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/16.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/16.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/17.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/17.png)

## Эксперимент с удаление и перемещением файлов

Создаем файлы will_be_deleted.txt (с текстом will_be_deleted)
и will_be_moved.txt (с текстом will_be_moved) и закоммитил их с комментарием
Prepare to delete and move.

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/18.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/18.png)

Удалите файл will_be_deleted.txt с диска и из репозитория.
Переименовывем (перемещаем) файл will_be_moved.txt на диске и в репозитории,
чтобы он стал называться has_been_moved.txt.
Закоммитьте результат работы с комментарием Moved and deleted.

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/18_1.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/18_1.png)

## Проверка изменения

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/19.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/19.png)

## Отправка изменений в репозиторий

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/20.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/20.png)

## Задание 2. Знакомство с документаций

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/21.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/21.png)

![alt text](https://github.com/mxssclxck/devops-netology/blob/main/img/22.png)
![alt text](https://gitlab.com/mrmxssclxck/devops-netology/-/tree/main/img/23.png)
