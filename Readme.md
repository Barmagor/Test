# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Проверка изменений
Для проверки того, какие правки были внесены, используем команду git diff. Команда проверяет, сравнивая текущую версию с закоммиченной.

## Отмена
Это q

### Инструкция по Markdown

## Заголовки
Чтобы делать заголовки в маркдаун, нужно использовать символ #. Количество этих значков позволяет выбрать уровень заголовка. Чем их больше, тем он дальше. Всего 6 уровней.

## Списки
Списки делаем через знак * или -, или +
* Первое
* Второе

- Первое
- Второе

+ Первое
+ Второе

Если нужна нумерация
1. Первое
2. Второе

## Разделители
Добавляем три *.

Первая строка
***
Вторая строка

## Цитаты
Чтобы сделать цитату ставим значок >. С их помощью можно делать несколько уровней цитирования, как с заголовками. 
> Все мы смертны 

Неизвестный мыслитель
> Сегодня он играет джаз, а завтра Родину продаст
>> Так писали в СССР

По словам Васи.

## Ссылки
Обычная ссылка делается по такой формуле, то есть так: 

[Ссылка](https://vk.com/badcomedian)

Или так, если ты хочешь, чтобы при наведении курсора вылезало пояснение:

[Ссылка](https://vk.com/badcomedian "известный паблик")

## Выделение текста

Курсив одна звёздочка, полужирный две. Смесь - три.

*Курсив* **полужирный** ***полужирный курсив***

## Изображение
Его вставляют по такой схеме:

![Имя]() и далее адрес на ПК.

Но если изображения из сети, можно так:

![Имя](https://yandex.ru/images/search?text=мрачная%20эстетика&from=tabbar&pos=1&img_url=https%3A%2F%2Fsun9-63.userapi.com%2Fimpf%2F-tKaQMhRg0CTgVSexSK_YrNB5zhuVcKk0W7UfQ%2F6jiOXzHaYtE.jpg%3Fsize%3D604x403%26quality%3D96%26sign%3D6188d35ad2cb7cbab86f274ce6a18060%26type%3Dalbum&rpt=simage "Поле")

Тест
  
Протестировали
