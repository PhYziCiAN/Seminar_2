# Семинар

# Система контроля версий Git

## Что такое Git?
Git - это одна из распределенных систем контроля версий. Позволяет управлять версионностью файлов, откатываться при необходимости, создавать ветки и сливать их.
## Подготовка репозитория
Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью команды *git init*, примененной в папке с будущим репозиторием.
## Создание "сохранений"
Для создания сохранения необходимо выполнить фиксация, через команду *get commit*. Для всех измененных файлов необходимо использовать *git add* или использовать ключ *-a* при фиксации.
## Перемещение между сохранениями
Перемещаться между коммитами или ветками можно с помощью команды *git checkout*
Отменять изменения можно с помощью команд *git revert*, *git reset <номер коммита>*
## Журнал изменений
Вызывается командой *git log*. В журнале изменений можно увидеть список коммитов текущей ветви.

## Ветки в Git
Собственно ветки нужны для совместной работы над проектом. Ветки создаются командой *git branch _имя ветки_* либо
*git checkout -b <имя ветки>*

## Скачивание удаленного репозитория
