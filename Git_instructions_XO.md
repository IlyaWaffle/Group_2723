# This is my chort comments to Git

## From lesson 1

* git --version            *(check install git)*
* git --init               *(create repozitory DIR)*

* git status                *(check current status)*
* git add ./file_name.ext   *(add file to contol GIT)*
* git add .                 *(add all files to control GIT)*
    !!! - ONLY after save files
* git commit -m "message"   *(create comment for last updete)*
* git commit -a -m "message" *(add + commit)*
* git log                   *(show all information about work)*
    Q - return to terminal

* git checout ...number     *(go to version Number...(min 4 ))*
* git checout master        *(return to last version file)*
* git diff                  *(show difference beetwin files)*

## From lesson 2

* git branch                *(show names of branches)*
* git branch new_name       *(create new branch with new_name)*
* git checkout new_name     *(go to new_branch)*
* git checkout master       *(return to master branch)*
* git merge new_name        *(merge (add) data from new_branch to current branch)*
* git -d old_branch         *(delete old_branch after merge)*
* git -D old_branch         *(delete old_branch without merge)*
* git log - graph           *(show graph with branches)
* .gitignore                *(create file in repository + write file names in __.gitignore__)*

## From lesson 3

### Совместная работа Git & GitHub

* Зарегистрироваться в GitHub
* Создать репозиторий в GitHub
* git clone {HTTP name} - клонировать в пустую папку будет создан локальный репозиторий аналог GitHub 
* или в обратную сторону
* в первый раз команды даст GitHub что-то типа:
* git remote add origin https://github.com/X-Oleg/Lessons-CheckVersions.git
* git branch -M main
* git push -u origin main
* и пройти аутентификацию (логин + пароль)

* в дальнейшем достоаточно:
* git push - отправлять на GitHub или
* git pull - забирать с GitHub (одновременно сливает ветки)


### Как сделать pull request

* Делаем fork репозитория на свой аккаунт
* Делаем clone СВОЕЙ версии репозитория в локальную папку
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (сохраняем, добавляем, делаем коммиты)
* Push - Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку Compare & pull request и затем Create pull request



# Инструкция для работы с MarkDown


## Выделение текста

*Курсив* - обрамить (*)

**Полужирный** - обрамить (**)

_курсив выриант 2_ (_обрамить)

__полужирный вариант 2__ (__обрамить)

Одновременно _курсив **и полужирный**_

## Списки

* Ненумерованные списки - (* элемент списка)

или 
+ Ненумерованные списки (+ элемент списка)

1. Нумерованные списки - (1. элемент списка)

## Работа с изображениями

для работы с изображениями - (![text](img_name))


![my lending](QR.jpg)

## Ссылки

## Работа с таблицами

## Цитаты

## Заключение

