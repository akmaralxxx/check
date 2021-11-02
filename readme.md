# Инструкция по работе с git

## что такое git?
Git - это одна из реализаций распределенных систем контрля версий. Git Позволяет управлять нашими изменениями, создавать фиксации, ветки, а так же сливать их.

## Подготовка репозитория
Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью применения в папке команды *git init*

## Создание сохранений

## Журнал изменений

## Перемещение между сохранениями
Перемещаться между сохранениями можно с помощью команды *git checkout*. Для этого достаточно применить команду *git checkout <номер коммита>*. 
Можно отменить изменения с помощью команд:
*git reset* и *git revert*
*git revert <номер коммита>* отменит изменения до указанной версии и создаст новый коммит.
*git reset --hard <номер коммита>* отменит изменеия до указанного коммита и затрет всю историю изменений после этого коммита. 

## Ветки в git

## Слияние веток и решение конфликтов

## Удаление веток

## Скачивание удаленного репозитория
