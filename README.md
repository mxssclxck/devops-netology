# devops-netology
# Домашнее задание к занятию «Основы Git» - Никоноров Денис - FOPS-6

## Задание 1.

После регистрации или авторизации в GitLab создайте новый проект, нажав на ссылку Create a projet. 
Желательно назвать также, как и в GitHub — devops-netology

![alt text](img/1.png)

Перейдите на страницу созданного вами репозитория, URL будет примерно такой: https://gitlab.com/YOUR_LOGIN/devops-netology.
Изучите предлагаемые варианты для начала работы в репозитории в секции Command line instructions.

![alt text](img/2.png)

Запомните вывод команды git remote -v.
Из-за того, что это будет наш дополнительный репозиторий,
ни один вариант из перечисленных в инструкции (на странице вновь созданного репозитория) нам не подходит.
Поэтому добавляем этот репозиторий, как дополнительный remote,
к созданному репозиторию в рамках предыдущего домашнего задания:
 git remote add gitlab git@gitlab.com:mrmxssclxck/devops-netology.git.
Отправьте изменения в новый удалённый репозиторий git push -u gitlab main.
Обратите внимание, как изменился результат работы команды git remote -v.

![alt text](img/3.png)

## Задание 2. Теги

Создайте легковестный тег v0.0 на HEAD-коммите и запуште его во все три добавленных на предыдущем этапе upstream.
Аналогично создайте аннотированный тег v0.1.
Перейдите на страницу просмотра тегов в GitHab (и в других репозиториях) и посмотрите, чем отличаются созданные теги.
в GitHub — https://github.com/YOUR_ACCOUNT/devops-netology/releases;
в GitLab — https://gitlab.com/YOUR_ACCOUNT/devops-netology/-/tags;

Легковестный тег у меня v0.1, а аннотированный v0.1.1

![alt text](img/4.png)

Как выглядят теги в GitLab

![alt text](img/5.png)

И Github

![alt text](img/6.png)

## Задание 3. Ветки

При просмотре лого найден коммит d148fdc825732ade2f355c76fff1b3464748bc4f prepare to delete and move

И выполнена команда git checkout <hash_commit>

![alt text](img/7.png)

Сделана новая ветка fix и отправлена в репозиторий в GitHub

![alt text](img/8.png)

Как выглядит ветвление в GitHub

![alt text](img/9.png)

Вывод git log 

![alt text](img/10.png)

## Задание 4. Упрощаем себе жизнь

Изменил файл README.md выполняя задание 4 в IDE PyCharm

![alt text](img/11.png)