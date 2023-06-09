# **Инструкция по работе с Git**

![emblem](git.JPG) 

Система контроля версий Git нужна для того, чтобы вернуть файлы к состоянию, в котором они были до изменений.

## Создание локального репозитория

Чтобы создать (инициализировать) новый локальный репозиторий нужно в терминале (находясь в нужной папке) ввести команду:

    git init

# Проверка состояния репозитория

Чтобы проверить состояние репозитория нужно в терминале ввести команду:

    git status

## Добавление или подготовка файла к команде commit

Чтобы добавить или подготовить файл к коммиту необходимо в терминале ввести команду:

    git add \<filename>

## Помещение всех файлов (которые не перчислены в .gitignore) в весь репозиторий

Чтобы поместить (добавить) все файлы в репозиторий нужно в терминале ввести команду:

     git add .

## Запись индексированных изменений в репозитории Git

Чтобы записать (зафиксировать) индексированные изменения в репозитории Git нужно в терминале ввести команду:

    git commit

## Фиксация изменений

Чтобы зафиксировать изменения нужно в терминале ввести команду:

    git commit -m

## Просмотр и фильтровка  истории проекта

Чтобы просматривать и фильтровать (корректировать) историю проекта нужно в терминале ввести команду:

    git log

## Отображение всех коммитов только с первой частью хэша и сообщением о фиксации

Чтобы отобразить ваши прошлые коммиты нужно в терминале ввести команду:

    git log --oneline

## Переключение на основную ветку

Чтобы переключиться на основную ветку нужно в терминале ввести команду:

    git checkout master

## Отображение разницы между коммитами

Чтобы увидеть (отобразить) разницу между коммитами нужно в терминале ввести команду:

    git diff

## Ветвления в Git

Ветвления нужны для работы над разными версиями проекта.

### Просмотр существующих веток

Для просмотра имеющихся веток используется команда:

    git branch

### Создание новой ветки

Для создания новой ветки используется команда:

    git branch <branch_name>

### Переключение между ветками

Для того чтобы переключиться на другую ветку используется команда:

    git checkout <branch_name>

### Слияние веток

Для того чтобы влить одну ветку в текущую нужно использовать команду:

    git merge

### Сброс проекта до нужного коммита

Чтобы сбросить состояние проекта до нужного коммита используется команда:

    git reset

### Отмена слияния веток

Для того чтобы отменить слияние веток используется команда:

    git merge -abort
### Добавление новой ветки и переход на неё

Чтобы добавить новую ветку и сразу перейти на неё используется команда:

    git checkout -b branchname

### Вызов внешней программы слияний при возникновении проблемы

Для того чтобы вызвать внешнюю программу слияний при возникновении проблемы слияний используется команда:

    git mergetool
