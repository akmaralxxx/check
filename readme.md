# Инструкция по работе с git и с GitHub

## Что такое система контроля версий?
Место хранения кода для разработчиков со всеми изменениями и версиями и возвращаться в определенную версию при необходимости.

## что такое git?
Git - это одна из реализаций распределенных систем контрля версий. Git Позволяет управлять нашими изменениями, создавапапке команды *git init*

## Подготовка репозитория

Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью применения в папке команжы *git init*

## Создание сохранений
Мы можем создавать сохранения наших версий файлов. Такие "сохранения" называются Фиксациями или коммитами. Cделать коммит можно с помощью команды *git commit* и **Обязательно** использовать флаг -m после чего в кавычках написать сообщение.

## Журнал изменений
Измененные файлы необходимо сохранить и проверить командой *git status*, в случае, если не сохранился файл, набрать команду *git add .*, *git add <file>*, или со сопроводительным сообщением *git commit -a -m "message"*.

## Перемещение между сохранениями
Перемещаться между сохранениями можно с помощью команды *git checkout*. Для этого достаточно применить команду *git checkout <номер коммита>*. 
Можно отменить изменения с помощью команд:
*git reset* и *git revert*
*git revert <номер коммита>* отменит изменения до указанной версии и создаст новый коммит.
*git reset --hard <номер коммита>* отменит изменеия до указанного коммита и затрет всю историю изменений после этого коммита. 

## Ветки в git
Новая ветка создаётся с помощью команды *git branch <branch-name>*

## Слияние веток и решение конфликтов
Слияние веток позволяет нам обьединять несколько файлов в одну ветку, позволяя избавляться от лишних веток. Действие можно совершить, применив команду *git merge <branch-name>*. Конфликт может вознивать в случае, если в разных версиях на одну и ту же строку записала информация. Разрешить можно выбрав один из правильных вариантов, иногда система сама подсказывает, как можно решить проблему.


Разрешение конфликта.
## Удаление веток
Удалить ветку можно с помощью команды *git branch -d*

## Скачивание удаленного репозитория


