[< к содержанию](./readme.md)

## git add

**git add *[файл]***- добавляете файл в индекс

Создание репозитория
Теперь вы готовы к работе с Git локально на компьютере.

Создадим наш первый репозиторий. Для этого пройдите в папку вашего проекта.

#Для Linux и MacOS путь может выглядеть так /Users/UserName/Desktop/MyProject
#Для Windows например С://MyProject
cd <путь_к_вашему_проекту>

#Инициализация/создание репозитория
git init
Теперь Git отслеживает изменения файлов вашего проекта. Но, так как вы только создали репозиторий в нем нет вашего кода. Для этого необходимо создать commit.

#Добавим все файлы проекта в нам будующий commit
git add .
#Или так
git add --all

#Если хотим добавить конкретный файл то можно так
git add <имя_файла> 

#Теперь создаем commit. Обязательно указываем комментарий.
#И не забываем про кавычки
git commit -m "<комментарий>"
Отлично. Вы создали свой первый репозиторий и заполнили его первым commit.

Процесс работы с Git
Не стоит после каждого изменения файла делать commit. Чаще всего их создают, когда:

Создан новый функционал

Добавлен новый блок на верстке

Исправлены ошибки по коду

Вы завершили рабочий день и хотите сохранить код

Это поможет держать вашу ветки в чистоте и порядке. Тем самым, вы будете видеть историю изменений по каждому нововведению в вашем проекте, а не по каждому файлу.

```баш=
git add .
```