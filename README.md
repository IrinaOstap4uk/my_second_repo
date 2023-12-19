# Создали my_second_repo

Далее следуем инструкции из github:

* echo "# my_second_repo" >> README.md 
Создаем файл README
* git init
Инициализируем файл
* git add README.md
Добавляем содержимое файла 
* git commit -m "first commit"
Добавляем содержимое файла в репозиторий
* git branch -M main
Переименвываем главную ветку master в main
* git remote add origin https://github.com/IrinaOstap4uk/my_second_repo.git
Связываем свой локальный репозиторий и удаленный
* git push -u origin main
Отправляем информацию в свой удаленный репозиторий

Делаем изменение в файле через github, далее создаем коммитт.

Через команду
```sh
git pull
```
запросили у сервера изменения.

Данные изменения появились в локальном репозитории. 

Создали новую ветку git newbranch и делаем изменения файла уже в новой ветке.

Создаем конфликтную ситуацию push/pull и разрешаем ее.
