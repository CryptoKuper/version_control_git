# Инструкция по языку MarkDown

Новая строка - это олна пустая строка

**Полужирный текст**

*Курсив текст*

## Цитирование
> Первый уровень
>> Второй уровень

## Списки
### Ненумерованные списки
* Лист 1
* Лист 2
### Нумерованные списки
1. Лист 1
2. Лист 2
3. Лист 3

## WEB ссылки
Текст [пример ссылки](http.example.com "Всплывающая подсказка")

## Работа с таблицами

Буква | Цифра | Символ
------ | ------|----------
a      | 4     | $
x      | 365    | (
b      |       | ^  

Буква|Цифра|Символ
---|---|---
a|4|$
 |365|(
b| |^  

Column | Column
------ | ------
\| Cell \|| \| Cell \|  


Column | Column | Column
:----- | :----: | -----:
Left   | Center | Right
align  | align  | align

## Картинки

### Это яблоко

![apple](apple.jpg)

### Это апельсин

![orange](orange.png)

## Работа с удаленными репозиториями

### Клонирование удаленного репозитория
Чтобы клонировать удаленный репозиторий, используйте команду:

git clone <url репозитория>

### Просмотр удаленных репозиториев
Чтобы просмотреть все удаленные репозитории, используйте команду:

git remote -v

### Добавление удаленного репозитория
Чтобы добавить новый удаленный репозиторий, используйте команду:

git remote add <имя> <url репозитория>

### Отправка изменений в удаленный репозиторий
Чтобы отправить изменения в удаленный репозиторий, используйте команду:

git push <удаленный репозиторий> <ветка>



