# Инструкция по работе с Git

## Установка VScode и Git
https://code.visualstudio.com/download

https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git


## Начальные настройки

*git config --global user.name "Ваше имя английскими буквами" например: Denis*

*git config --global.user.email ваша почта@exemple.com*
## Команды Git
*git init* - **Инициализация локального репозитория**

*git status* - **получить информацию от git о его текущем состоянии**

*git add Имя.расширение(Md) файла* - **добавить файл или файлы к следующему коммиту**

git add .\ - **добавить все файлы для отслеживания**

*git commit -m "Комментарий"* - **создание коммита**

*git log* - **Выводит на экран истории всех коммитов с их хэш-кодами**

*git log --graph* - **команда для вывода коммитов с визуализацией**

*git checkout название ветки* - **команда для переключениями между ветками**

*git checkout* master - **Вернуться к актуальному состоянию и продолжить работу**

*git checkout -b Название ветки* - **Создай ветку и переключись на её**

*git diff* - **Увидеть разницу между текущим файлом и закоммиченым файлом**

*echo "#Инструкция по работе с Git" >> instruction.md* - **Создать файл из терминала**

*git branch название ветки* - **команда для создания новой ветки**

*git branch* - **команда для вывода всех веток на экран**

*git branch -d название ветки* - **команда для удаления ветки**

*git merge название ветки* - **команда для слияния веток**

*git merge название ветки* - **команда для отмены слияний**

*clear* - **Очистить терминал**

*ls* - **Эта команда выводит список файлов в данной папке**

## Работа с изображениемы

**Чтобы вставить изображение в текст. Нужно скопировать файл изображения в папку и написать в md - *![Любое сообщение(выводится вместо изображения в случае,когда имя фото указано с ошибкой)](Название файла.расширение)*


**Для того чтобы игнорировать файл(картинку)** - нужно создать файл *.gitignore* , добавить название файла под цифрой 1., например - *teftelka.jpg*. Далее *git add .gitignore* и *git commit -m "Добавили gitignore файл"*


# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звёздочками (*), или знаком нижнего подчёркивания (_). Например, *вот так*, или _вот так_. 

Чтобы выделить текст полужирным, необходимо обрамить его двойными звёздочками (**), или двойным знаком нижнего подчёркивания (__). Например, **вот так**, или __вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например:
_текст может быть выделен курсивом и при этом быть **полужирным**_  
## Списки
Чтобы добавить ненумерованые списки, необходимо пункты выделить звёздочкой (*), или знаком +. Например:
* Элемент 1 
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованые списки, необходимо просто их пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт
3. Третий пункт

# Работа с удалёнными репозиториями в Git

## Команды 

*git clone адрес репозитория* - **Эта команда позволяет склонировать внешний репозиторий на наш ПК**

*git pull* - **Эта команда позволяет скачать всё из текущего репозитория и автоматически сделать merge с нашей версией (из интернета)**

*git push* - **Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории**

*git remote add origin ссылка* - **Привязка локального репозитория к удалённому**

*cd название папки* - **Эта команда позволяет перейти к другой папке change directory**


## Как сделать pull request

* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаём новую ветку и в НЕЁ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем pull request

## Как внести изменения, созданые после копирования репозитория
* Заходим на удалённый репозиторий GitHub
* Нажимаем Fetch Upstream
* Нажимаем Fetch and merge






















