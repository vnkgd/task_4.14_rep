## git add


**Команда git add *[файл]*** добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита. По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита.

Это одна из ключевых команд Git, мы упоминали о ней десятки раз на страницах книги. Ниже перечислены наиболее интересные варианты использования этой команды.

Знакомство с этой командой происходит в главе Отслеживание новых файлов.

О том как использовать git add для разрешения конфликтов слияния написано в главе Основные конфликты слияния.

В главе Интерактивное индексирование показано как использовать git add для добавления в индекс лишь отдельных частей изменённого файла.

В главе Деревья показано как эта команда работает на низком уровне, чтобы вы понимали, что происходит за кулисами.

Как программный код (инлайн вставка):

` 
git add .
`

или участок кода, с указанием языка, на котором происходит интерпритация:

``` bash=
git add .
```

[< Вернуться на главную страницу (Содержание)](./readme.md)