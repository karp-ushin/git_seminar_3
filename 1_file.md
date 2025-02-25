![](git_logo.png)
# Инструкция для работы с Git


## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Начало работы

### Подготовка репозитория
Для создание репозитория необходимо выполнить команду 
>git init

в папке с репозиторием и у Вас создаcтся репозиторий (появится скрытая папка .git).

### Добавление файлов
Команда
>git add *file_name*

добавляет файл *file_name* в Staging Area Git.

### Сохранение изменений
Команда
>git commit -m "*Message*"

сохраняет изменения в репозиторий Git и добавляет сообщение *Message*.

### Журнал
Команда
>git log

показывает информацию о текущей и более ранних сохранённых конфигурациях.

### Отслеживание сделанных изменений
производится командой
>git diff

### Навигация  
между сохраненными конфигурациями производится командой
>git checkout *branch id*

Здесь в *branch id* достаточно указать первые четыре символа.


### Состояние  
Отображение состояния рабочей папки и репозитория производится командой
>git status

## Работа с разными ветками

### Список ветвей  
Выводится командой
>git branch

### Создание ветви
Новая ветвь создается командой
>git branch *branch name*
### Удаление ветви  
производится командой
>git branch -d *branch_name*
### Слияние ветвей
Команда
>git merge *branch_name*

присоединяет ветвь с именем *branch_name* к текущей ветке.

## Работа с удаленным репозиторием

### Клонирование репозитория
Команда
>git clone *repo adress*

копирует репозиторий, находящийся по адресу *repo adress*, и настраивает его как удаленный для копии.

### Скачивание с удаленного репозитория

Команда 
>git pull 

позволяет скачать все из репозитория и автоматически
сделать merge. 

### Запись в удаленный репозиторий
Команда
>git push

позволяет отправить нашу версию репозитория на внешний
репозиторий.

## Список команд
* [git init](#подготовка-репозитория)
* [git add](#добавление-файлов)
* [git commit](#сохранение-изменений)
* [git log](#журнал)
* [git diff](#отслеживание-сделанных-изменений)
* [git checkout](#навигация)
* [git status](#состояние)
* [git branch](#список-ветвей)
* [git branch *branch_name*](#создание-ветви)
* [git branch -d *branch_name*](#удаление-ветви)
* [git merge](#слияние-ветвей)
* [git clone](#клонирование-репозитория)
* [git pull](#скачивание-с-удаленного-репозитория)
* [git push](#запись-в-удаленный-репозиторий)