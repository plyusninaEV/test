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
______
# Использование эмодзи (emoji)
В самом тексте можно использовать эмодзи, например написать вот так:

✅ Это уже сделано

❎ Я не буду это делать

🔲 делать или не делать, вот в чем вопрос?

В оригинале это выглядит так (в конце строки четыре (4) пробела для того, что бы был переход на новую строку):

`:white_check_mark: Это уже сделано    
:negative_squared_cross_mark: Я не буду это делать    
:black_square_button: делать или не делать, вот в чем вопрос?   ` 

