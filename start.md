Начало работы с GIT

1. Зарегистрироваться в GIT
2. Установить Visual Studio Code
3. В VSCode Создать папку с проектом на компе
4. В VSCode Создать файлы
5. В VSCode Запустить терминал
6. Создать в GIT репозиторий
7. В VSCode в Терминале ввести поочерёдно команды со страницы, которая открывается при создании репозитория.

```
git init  // создание репозитория на локальной машине
git add . //означает, что все файлы из папки с проектом.
Либо конкретный файл:
            git add readme.md
git commit -m "first commit" //комментаруем (коммитим) что изменили, кратко и по английски желательно
git branch -M main //создаём ветку без этой команды не пушилась, а значит она важна
git remote add origin https://github.com/vnkgd/task_4.14_rep.git   //в наш репозиторий
git push -u origin main  // main это ветка, главная, можно написать master
```

Может попросить дать разрешение доступа нашему кому в GIT, дать.

8. Обновить страницу на гитхабе, проверить, появились ли наши файлы.
9. После изменений сохраняемся (CTRL+S) и в Терминале вводим команды:

```
git add . //означает, что все файлы из папки с проектом. 
git commit -m "readme.md and .gitignore.md update and added files" // коммитим что изменили
git push

```

10. Обновляем страницу на гитхабе и проверяем файлы.
11. Можно выложить на гит хостинг страницу, которой не нужен сервер для исполнения кода и база данных.
Внимание!!! Если мы удаляем на гитхабе файлы, то при следующейм пуше он ругнётся, скажет, что эти файлы на локальной машине есть, а на в репозитории на гитхабе нет.
Команда git pull удалит эти файлы на локальной машине.



[< Вернуться на главную страницу (Содержание)](./readme.md)