## Шаг 1. Скачать ПО для работы ##
Скачать Git по ссылке:

* [GIT](https://git-scm.com/downloads)

Скачать VS code по ссылке:

* [VS Code](https://code.visualstudio.com/)

Выполнить регистрацию на GITHUB для дальнейшей работы

* [GITHUB](https://github.com/?ysclid=l8ihoqggdd358761195)

## Шаг 2. Создать папку для работы и выбрать рабочий файл ##

* Инициализировать раабочий репозиторий необходимо командой (*Выбрать рабочую папку*):

```git init```

* Добавить файл как отслеживаемый командой(*Выбрать рабочий файл*):

```git add```

* Все внесеенные в текущей версии файла изменения, необходимо зафиксировать командой:

```git commit```

* Для просмотра истории изменений (*commit*) требуется команда:

```git log```

* Для проверки текущего статуса репозитория необходимо использовать команду:

```git status```

* Для просмотра изменений до внесения в репозиторий используется команда:

```git diff```

### 1. Вызвать для работы терминал 
### 2. Определить необходимый для работы репозиторий путем ввода команды _git init_
### 3. Выбрать необходимый для отслеживания изменений файл командой _git add_
### 4. После внесения каких лтбо изменений их необходимо зафиксировать командой _git commit -m ""_
### 5. Для отслеживания изменений в репозитории, воспользоваться командой _git log_
 * _git log --oneline_ позволяет вывести log в упрощенном варианте
 * _git log --graph_ позволит показать log с учетом измениний по веткам
### 6. Для перехода по commit необходимо воспользоваться коммандой git checkout и номер commit (***Достаточно указать первые 4-5 символов commit***) 
### 7. Команда _git status_ выведет текущий статус репозитория
### 8. При помощи команды _git branch_ увидеть количество и наименование существующих в рамках репозитория веток.
* Добавление веток происходит по команде _git branch (***наименование ветки***)_
* Удаление веток происходит по команде _git branch -d (***наименование ветки***)_
* Переход между ветками происходит по команде _git checkout (***наименование ветки***)_
### 9. Слияние веток происходит по каманде _git merge (имя ветки)_ из той ветки куда вы хотите добавить изменения из указанной ветки.
## Шаг 3. Оформление текста в Markdown ##

 1. Заголовки
 Заголовки различного порядка формируются при помощи символа # перед текстом. Чем больше символов применяется, тем ниже уровень заголовка.

 2. Списки
 * Нумерованные (Достаточно указать номер и поставить точку 1.)
 * Ненумерованные (Достаточно поставить звездочку пере текстом и отступ * )

 3. Текст
 * Курсив ( для выделения текста *курсивом* используются * до и после текста без пробела или символ _)
 * Жирный (для выделения текста **жирным** используется ** либо __) до и после текста.
 * Зачеркнутый ( для выделения текста ~~зачеркиванием~~ используется символ ~ до и после текста)
  
Так же можно применить к тексту два вида стилей *** до и после. Получим ***Жирный курсив***
  
4. ~~Шпаргалка~~

![](tomarkdown.png)

## Шаг 4. Добавление ссылок и файлов

Для сопровождения своего текста дополнительными файлами или ссылками, необходимо указать путь файла или ссылки в следующей форме:

[Наименование файла или ссылки( то что отразилось на экране)] (путь к файлу) - [] () - без пробела
если перед конструкцие [] () поставить ! то вместо ссылки на файл будет сразу отражен сам файл.

## Шаг 5. Работа с удаленными репозиториями
 
1.	Fork – копирование репозитория из стороннего аккаунта
2.	Git clone – клонирование репозитория в локальный
3.	Создаем дополнительную ветку
4.	Вносим свои изменения в рамках ветки
5.	Git push – отправляем изменения из локального в удаленный репозиторий
6.	Git pull – синхронизируем свой локальный репозиторий с удаленным

