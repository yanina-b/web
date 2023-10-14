# лекция 1 #


## Стартовая разметка ##

***DOCTYPE html*** - это декларация типа документа. Так браузер узнает, на каком языке и с какими технологиями он был создан.	

***html*** - корневой элемент HTML-документа. Сообщает браузеру, что это HTML-документ. Является контейнером для всех остальных html-элементов.

***head*** - Элемент-контейнер для метаданных HTML-документа.

***meta*** - Используется для хранения дополнительной информации о странице. Эту информацию используют браузеры для обработки страницы, а поисковые системы — для ее индексации.

***body*** - Представляет тело документа (содержимое, не относящееся к метаданным документа).


## **Базовые теги:** ##
1. Для хранения контента
(блоки, области,
разделы)
2. Для создания контента
(Заголовки, параграфы, списки и тд.)

## **📚Для хранения контента:** ##
1. ***section*** - определяет логическую область (раздел) страницы, обычно с заголовком.
2. ***footer*** - определяет завершающую область (нижний колонтитул) документа или раздела.
3. ***header*** - секция для вводной информации, группы навигационных ссылок. Может содержать заголовки, логотип, информацию об авторе.
4. ***nav*** - раздел документа, содержащий ссылки для навигации по сайту.
5. ***div*** - элемент-контейнер для разделов HTML-документа. Используется для группировки блочных элементов для форматирования стилями.

## **Для создания контента:🎸** ##
1. ***h1-h6*** - создают заголовки шести уровней для связанных с ними разделов.
2. ***p*** - параграфы в тексте.
3. ***a*** - создает гипертекстовые ссылки.
4. ***span*** - контейнер для строчных элементов.
5. ***ul*** - создает маркированный список.
6. ***li*** - элемент маркированного или нумерованного списка.
7. ***ol*** - числовой или алфавитный нумерованный список.
8. ***img*** - встраивает изображения в HTML-документ с помощью атрибута src, значением которого является адрес встраиваемого изображения.

## **Они делятся на** ##
1. Блочные:
   - section
   - div
   - header
   - nav
   - h1-h6
   - p
   - ol
   - ul
   - footer
2. Строчные:
   - a
   - span
   - img
   - li


## **Формы и поля** ##
- ***form*** - форма для сбора и отправки на сервер информации от пользователей. Не работает без атрибута action.
- ***input*** - cоздает многофункциональные поля, в которые пользователь может вводить данные.
- ***select*** - элемент управления, позволяющий выбирать значения из предложенного множества. Варианты значений помещаются в <option>.
- ***option*** - определяет вариант/опцию для выбора в раскрывающемся списке <select>.
- ***textarea*** - cоздает большие поля для ввода.
- ***label*** - добавляет текстовую метку для <input>.
- ***button*** - cоздает интерактивную кнопку. Элемент может содержать текст или изображение.


## **Методы передачи данных из формы:** ##
1. ***get*** - передает данные на сервер через адресную строку браузера. Имена и значения переменных присоединяются к адресу сервера после знака ? и разделяются между собой знаком &.
2. ***post*** - применяется для пересылки данных больших объемов, а также конфиденциальной информации и паролей. Данные, отправляемые с помощью этого метода, не видны в заголовке URL, так как они содержатся в теле сообщения.


## **⚔️Виды атрибута type тега input** ##
- ***checkbox*** - превращает поле ввода во флажок, который можно установить или очистить.
- ***color*** - генерирует палитры цветов в поддерживаемых браузерах, давая пользователям возможность выбирать значения цветов в шестнадцатеричном формате.
- ***date*** - позволяет вводить дату в формате дд.мм.гггг.
- ***datetime-local*** - позволяет вводить дату и время, разделенные прописной английской буквой Т по шаблону дд.мм.гггг чч:мм.
- ***email*** - браузеры, поддерживающие данный атрибут, будут ожидать, что пользователь введет данные, соответствующие синтаксису адресов электронной почты.
- ***file*** - позволяет загружать файлы с компьютера пользователя.
- ***hidden*** - скрывает элемент управления, который не отображается браузером и не дает пользователю изменять значения по умолчанию.
- ***month*** - позволяет пользователю вводить год и номер месяца по шаблону гггг-мм.
- ***number*** - предназначено для ввода целочисленных значений. Его атрибуты min, max и step задают верхний, нижний пределы и шаг между значениями соответственно. Эти атрибуты предполагаются у всех элементов, имеющих численные показатели. Их значения по умолчанию зависят от типа элемента.
- ***radio*** - создает переключатель — элемент управления в виде небольшого кружка, который можно включить или выключить.
- ***search*** - обозначает поле поиска, по умолчанию поле ввода имеет прямоугольную форму.
- ***password*** - создает текстовые поля в форме, при этом вводимые пользователем символы заменяются на звездочки, маркеры, либо другие, установленные браузером значки.
- ***range*** - позволит создать такой элемент интерфейса, как ползунок, min / max — позволяют установить диапазон выбора.
- ***text*** - создает текстовые поля в форме, выводя однострочное текстовое поле для ввода текста.
- ***time*** - позволяет вводить время в 24-часовом формате по шаблону чч:мм. В поддерживаемых браузерах оно отображается как элемент управления в виде числового поля ввода со значением, изменяемым с помощью мыши, и допускает ввод только значений времени.
- ***url*** - поле предназначено для указания URL-адресов.
- ***week*** - соответствующий инструмент-указатель позволяет пользователю выбрать одну неделю в году, после чего обеспечивает ввод данных в формате нн-гггг. В зависимости от года число недель может быть 52 или 53.


## Виды атрибута type тега button ##
1. ***submit*** - создает стандартную кнопку, активизирующую щелчком мыши. Кнопка собирает информацию с формы и отправляет ее для обработки.
2. ***reset*** - создает кнопку, которая очищает поля формы от введенных пользователем данных.

# Что нового из домашки 1 #
1. Если надо всё в одну строчку, то надо всё разместить в одном nav или div
2. form action = '#' - чтобы ничего никуда не отправлялось
3. ***placeholder*** - сделать надпись, которая будет координировать пользователя в том, что ему ввести внутри поля, необходимо использовать атрибут placeholder с тем значением внутри, которое вы хотите увидеть в поле
4. если просто нужна кнопка, то без input, просто button
5. знак, где все права защищены **©**
