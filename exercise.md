# Шпаргалка по работе с git
## Инициализация пользователя и электронной почты
* git config --global user.name "first and second name"
* git config --global user.email "email@domen.com"

## Инициализация нового или уже существующего репозиторя
* git init

## Добавление всех или отдельных файлов в область подготовленных файлов
* git add .
* git add name.txt

## Проверка статуса репозитория
* git status

## Создание коммита с однострочным сообщением либо сообщение через редактор
* git commit -m "Your message"
* git commit

## Просмотр логов, просмотр логов с изменениеями и односмтрочный просмотр логов
* git log
* git log -p
* git log --oneline

## Изменение последнего коммита
* git commit --amend -m "message"