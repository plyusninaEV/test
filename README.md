# Описание разметки файла README.md

Для описания проектов на GitHub используется README.md, который пишется на языке разметки markdown. 
Для форматирования текста на GitHub используются достаточно простые правила. Я перечислю основные и достаточные, так как не претендую на полноту официального руководства.

Текст можно обработать в любом простом текстовом редакторе, например в Notepad++, которым пользуюсь сам. А можно и прямо на GitHub редактировать файл в он-лайн режиме.

Стилистическая разметка должна быть такой:
Разбиение на абзацы производится вставкой пустой строки между ними (нажмите "Enter" после абзаца).

Горизонтальная полоса между абзацами - тег ` <hr> `- три или более звёздочек или дефисов

# Оглавление
_________

# Заголовки
Всего существует шесть уровней заголовков. Для того, чтобы создать заголовок, необходимо в начале строки добавить символы #, в количестве равном его уровню.
____
# Заголовок первого уровня
` # Заголовок 1 `

Заголовок первого уровня также можно создать:

` h1 заголовок первого уровня
===================== `

## Заголовок второго уровня

` ## Заголовок 2 `

Заголовок второго уровня также можно создать:

` Заголовок 2
----------- `
### Заголовок третьего уровня

` ### Заголовок 3 `

#### Заголовок четвертого уровня

` #### Заголовок 4 `

#####Заголовок пятого уровня

` ##### Заголовок 5 `

###### Заголовок шестого уровня

` ###### Заголовок 6 `
_________________
# Работа с выделением текста
` ~~Зачеркнутый текст~~ `

~~Зачеркнутый текст (Strikethrough)~~

Для выделения текста жирным или наклонным и их сочетания можно использовать комбинации * или _

` **Жирный текст (bold)** `

**Жирный текст (bold)** 

` *Наклонный текст (italic)* `

*Наклонный текст (italic)*

` ***Жирный наклонный текст (bold italic)*** `

***Жирный наклонный текст (bold italic)***

` __Жирный текст (bold)__ `

__Жирный текст (bold)__

` _Наклонный текст (italic)_ `

_Наклонный текст (italic)_

`___Жирный наклонный текст (bold italic)___ `

___Жирный наклонный текст (bold italic)___

`~~*__Тут странный текст__*~~ `

~~*__Тут странный текст__*~~

Верхние и нижние индексы

` 2^10^ C~n~^k^`

2^10^ C~n~^k^
______
# Использование эмодзи (emoji)
В самом тексте можно использовать эмодзи, например написать вот так:

✅ Это уже сделано

❎ Я не буду это делать

🔲 делать или не делать, вот в чем вопрос?

В оригинале это выглядит так (в конце строки четыре (4) пробела для того, что бы был переход на новую строку):

`:white_check_mark: Это уже сделано  `

`:negative_squared_cross_mark: Я не буду это делать`

`:black_square_button: делать или не делать, вот в чем вопрос?   ` 

Список работающих Эмодзи находится тут -> [emoji-cheat-sheet] (https://www.webfx.com/tools/emoji-cheat-sheet/)
______
# Использование цитирования в тексте

`> Цитата (уровень 1)   ` 
`> > Вложенная цитата (уровень 2) `   
`> > > Вложенная цитата (уровень 3)  `  

`> > Продолжение цитаты (уровень 2)  `  

`> Продолжение цитаты (уровень 1)    `

> Цитата (уровень 1)    
> > Вложенная цитата (уровень 2)    
> > > Вложенная цитата (уровень 3)    

> > Продолжение цитаты (уровень 2)    

> Продолжение цитаты (уровень 1)   

Внешний вид, конечно, не очень, но может и пригодиться.
____
# Подсветка кода
Если нужно выделить слово или фразу внутри строки, то используются одинарные обратные кавычки (`):
Для выделения в блоки - тройные:

```
    Здесь может быть
    Ваша реклама
```
_____
# Ссылки
` [Текст ссылки](https://htmlacademy.ru) `

Картинки ставятся как ссылки, только в начале добавляется восклицательный знак.

` ![Альт-текст](ссылка на картинку)`
______
# Вставка изображения
` ![Alt-текст](https://avatars1.githubusercontent.com/u/5384215?v=3&s=460 "Орк") `

## Вставка ссылки с картинкой на ролик с YouTube

Описание комбинации ` [![Тут текст](адрес до картинки)](ссылка на страничку YouTube) `
Пример:

`[![Тут текст](https://img.youtube.com/vi/RHPYGwVQB2o/0.jpg)](https://youtu.be/RHPYGwVQB2o)`
____
# Вставка таблиц
`| LEFT | CENTER | RIGHT |`

`|----------------|:---------:|----------------:|`

`| По левому краю | По центру | По правому краю |`

`| текст | текст | текст |`

| LEFT | CENTER | RIGHT |
|----------------|:---------:|----------------:|
| По левому краю | По центру | По правому краю |
| текст | текст | текст |
**Внимание:** Если в тексте таблицы нужно использовать символ "вертикальная черта - |", то в место него необходимо написать замену на комбинацию HTML-кода* &#124;, это нужно для того, что бы таблица не потеряла ориентации.
`*) - Можно использовать ASCII и/или UTF коды.`

**Пример:**
`| Обозначение | Описание | Пример регулярного выражения|`

`|----:|:----:|:----------|`

`| literal | Строка содержит символьный литерал literal | foo |`

`| re1&#124;re2 | Строка содержит регулярные выражения `rel` или `re2` | foo&#124;bar |`


| Обозначение | Описание | Пример регулярного выражения|
|----:|:----:|:----------|
| literal | Строка содержит символьный литерал literal | foo |
| re1&#124;re2 | Строка содержит регулярные выражения `rel` или `re2` | foo&#124;bar |
------
[Руководство по синтаксису для базового использования Markdown](https://docs.microsoft.com/ru-ru/azure/devops/project/wiki/markdown-guidance?view=azure-devops)
