# Шпаргалка по работе с git
### Инициализация пользователя и электронной почты
* git config --global user.name "first and second name or nickname"
* git config --global user.email "email@domen.com"

### Инициализация нового или уже существующего репозиторя
* git init

### Добавление всех или отдельных файлов в область подготовленных файлов
* git add .
* git add name.txt

### Проверка статуса репозитория
* git status

### Создание коммита с однострочным сообщением либо сообщение через редактор
* git commit -m "Your message"
* git commit

### Просмотр логов, просмотр логов с изменениеями и односмтрочный просмотр логов
* git log
* git log -p
* git log --oneline

### Изменение последнего коммита
* git commit --amend -m "message"

### Просмотр заданного коммита
* git show 1f915694954a74248d8226cbe34d0e81b8b08aa7
либо
* git show 1f9156

### Просмотр списка изменений
* git diff

### Отмена подготовленных и неподготовленных изменений
* git checkout namefile.txt

### Просмотр всех веток
* git branch

### Переключение на другую ветку
* git swith name_branch

### Слияние двух веток
* git merge name_branch

### Отображение журнала коммитов для всех веток
* git log --graph
* git log --graph --oneline --decorate

По всем веткам:
* git log --all --graph --oneline --decorate



# Работаем локально
### Отправка на github
* git push


# Работаем на github
### Отправка c github (стягиваем с сайта)
* git pull

### Алгоритм стягивания репозитория с github

1. git remote add origin https://github.com/userName/link.git
2. git branch -M main
3. git push -u origin main