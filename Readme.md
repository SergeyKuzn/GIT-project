# Инструкция по работе с MarkDown

Другой заголовок Pictures

## `Заголовки.`
> Чтобы добавить заголовок, необходимо поставить знак "#"
> и через пробел ввести текст заголоака. Заголовки имеют 6 уровней.
> Уровень заголовка определяет колличество знаков "#".

# [Инструкция по работе с GIT](#инструкция-brпо-работе-с-git)
## Заголовок 2
### Заголовок 3
#### Заголовок 4
##### Заголовок 5
###### Заголовок 6

## `Списки.`
> Списки могут быть `нумерованными` и `ненумеровнными`. 
>
> Чтобы создать ненумерованный список, необходимо поставить перед пунктом списка один из следующих знаков: * , - , +  и через пробел ввести название элемента списка.<br/>
> Чтобы создать нумерованный список, необходимо поставить перед пунктом списка число с точкой и через пробел ввести название элемента списка.

### Ненумерованные списки:
* Пункт 1
* Пункт 2
    - Подпунк 1 пункта 2
    - Подпунк 2 пункта 2
        - Подпунк 1 подпункта 2 пункта 2

> Можно создавать многоуровневые списки. Каждый уровень отделяется четырьмя (4) пробелами.
### Нумерованные списки:
1. Пункт 1
    + Подпунк 1 пункта 1
    + Подпунк 2 пункта 1
        + Подпунк 1 подпункта 2 пункта 1
2. Пункт 2
3. Пункт 3

## `Якорные ссылки. `
> Якорные ссылки применяются для для навигации внутри документа markdown.


## `Выделение в блоки.`
> Если нужно выделить блок с текстом, то используются тройные обратные кавычки (`). Дополнительно можно задавать язык кода внутри блока, указав его после первых трех кавычек.

``` python
    #Пример ввода кода на языке Python 
    for i in range(1, 10):
        print(i)
```
> Если нужно выделить `слово` или `фразу` внутри строки, то используются одинарные обратные кавычки (`):

## `Работа с изображениями.`

Базовый синтаксис Markdown для внедрения изображения:

> `![<alt text>](<folderPath>)`

Где `<alt text>` — краткое описание изображения, а `<folder path>` — относительный путь к нему. Заменяющий текст необходим для средств чтения с экрана для слабовидящих. Он также удобен при возникновении ошибок на сайте, из-за которых не удается воспроизвести изображение.

Знаки подчеркивания в замещающем тексте не отображаются должным образом, если они не экранированы с помощью префикса — обратной косой черты (\_). Но не стоит копировать имена файлов для использования в качестве замещающего текста.

### Шпаргалка по Git

![Шпаргалка по Git](/%D0%A8%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0%20%D0%BF%D0%BE%20Git.jpeg)

# Инструкция по работе с GIT

## `Что такое Git?`
Git - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте. Чаще всего его используют для кода, но можно и для других файлов. Например, для картинок - полезно для дизайнеров.

С помощью Git-a вы можете откатить свой проект до более старой версии, сравнивать, анализировать или сливать свои изменения в репозиторий.

**Репозиторием** называют хранилище вашего кода и историю его изменений. Git работает локально и все ваши репозитории хранятся в определенных папках на жестком диске.

Так же ваши репозитории можно хранить и в интернете. Обычно для этого используют три сервиса:
- GitHub
- Bitbucket
- GitLab

Каждая точка сохранения вашего проекта носит название **коммит** (commit). У каждого commit-a есть hash (уникальный id) и комментарий. Из таких commit-ов собирается ветка. **Ветка** - это история изменений. У каждой ветки есть свое название. Репозиторий может содержать в себе несколько веток, которые создаются из других веток или вливаются в них.

## `Основные команды Git.`

* `git config --global user.name "<ваше_имя>"`
* `git config --global user.email "<адрес_почты@email.com>"`
* `git init`
* `git add .`
* `git add --all`
* `git add <имя_файла> `
* `git commit -m "<комментарий>"`
* `git log`
* `git diff`
* `git clone`
* `git status`
* `git branch`
* `git merge`
* `git checkout`
* `git clean`
* `git fetch`
* `git pull`
* `git push`


> `git add .`  <br/>_Добавим все файлы проекта в наш будующий commit_ 
> 
> `git add <имя_файла>` <br/>_Если хотим добавить конкретный файл то можно так_
>
> `git status` <br/>_Получить информацию от git о его текущем состоянии_
>
> `git commit -m "<комментарий>"` <br/>_Создание коммита с комментарием_
>
> `git checkout` <br/>_Переход от одного коммита к другому_
>
> `git log` <br/>_Вывод на экран истории всех коммитов с их хеш-кодами_
>
> `git diff` <br/>_Увидеть разницу между текущим файлом и закоммиченным файлом_



