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

### **📚Для хранения контента:** ###
1. ***section*** - определяет логическую область (раздел) страницы, обычно с заголовком.
2. ***footer*** - определяет завершающую область (нижний колонтитул) документа или раздела.
3. ***header*** - секция для вводной информации, группы навигационных ссылок. Может содержать заголовки, логотип, информацию об авторе.
4. ***nav*** - раздел документа, содержащий ссылки для навигации по сайту.
5. ***div*** - элемент-контейнер для разделов HTML-документа. Используется для группировки блочных элементов для форматирования стилями.

### **Для создания контента:🎸** ###
1. ***h1-h6*** - создают заголовки шести уровней для связанных с ними разделов.
2. ***p*** - параграфы в тексте.
3. ***a*** - создает гипертекстовые ссылки.
4. ***span*** - контейнер для строчных элементов.
5. ***ul*** - создает маркированный список.
6. ***li*** - элемент маркированного или нумерованного списка.
7. ***ol*** - числовой или алфавитный нумерованный список.
8. ***img*** - встраивает изображения в HTML-документ с помощью атрибута src, значением которого является адрес встраиваемого изображения.

### **Они делятся на** ###
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
6. чтобы сделать большую ячейку для текста <***textarea*** name="comment" id="comment" cols="20" rows="5"></textarea>
7. ***target="_blank"*** - ссылка открывается в новой вкладке
- ***nav*** отвечает за навигационное меню. В нем размещаются любые ссылки для навигации по сайту.
- ***section*** содержит в себе основной контент страницы. Внутри него вы можете, на свое усмотрение, разбивать контент используя блоки div.
- ***footer*** отвечает за подпись сайта. Там всегда размещается копирайт, иногда политика конфиденциальности и частенько бывает ещё одна карта сайта.


# CSS #

***Панель разработчика*** – это средство в браузере позволяющее просматривать ошибки возникшие при загрузке страницы и взаимодействовать со страницей.
Быстро открыть её можно клавишей ***F12***, сочетанием клавиш ***Ctrl + Shift + I*** или ПКМ -> Просмотреть код (Исследовать элемент)

## Стили ##
👽 Стили можно прописывать в…
- …самом теге, при помощи ***атрибута style***: <p style="font-size: 18px;"> Это текст размером 18px</p>
- …***head*** внутри элемента ***style***: <style> p{...} a{...} </style>
- …***отдельном файле*** подключенном к html:
  <link rel="stylesheet" type="text/css" href="css/reset.css">
  <link rel="stylesheet" type="text/css" href="css/main.css">

## Как использовать стили ##
Стили подключенные через ***link*** или через ***head*** возможно применить при помощи ***классов*** или ***id***.
При этом, стили прописанные через ***атрибут style*** в теге будут иметь ***высший приоритет*** и применяться независимо от стилей в файле или head.

**html:**
<div class="title"> <h1 id="title_h1"></h1> <p>Курс <span>мемов</span> Web-разработки в РТУ МИРЭА</p> <a href="#">Присоединиться к беседе</a>  </div>

**css**
.title{
    text-align: center;
    margin-top: 75px;
}

#title_h1{
    text-transform: uppercase;
    font-size: 50px;
    font-weight: 700;
    text-decoration: underline;
}

.title p{
    margin-top: 16px;
    font-size: 25px;
}

.title p span{
    text-decoration: line-through;
    color: #525252;
}


## Важные CSS стили текстов ##
- ***font-size***: 18px - меняет размер шрифта
- ***font-weight***: 600 - меняет толщину шрифт
- ***line-height***: 15px - меняет межстрочный интервал
- ***color***: purple - меняет цвет шрифта
- ***font-family***: "Source Code Pro", sans-serif - меняет шрифт (название подключенного шрифта и семейство)
- ***text-transform***: uppercase - меняет регистр
- ***text-decoration***: underline - добавляет подчеркивание\зачеркивание\надчеркивание в зависимости от значения свойства
- ***text-align***: center - выравнивание текста

## 🧠 Другие важные CSS стили ##
- ***margin***: 18px 0 20px 10px - устанавливает величину отступа от каждого края
- ***padding***: 20px 10px - устанавливает значение полей вокруг содержимого элемента.
- ***width***: 100% - устанавливает ширину блочных элементов
- ***height***: 800px - Устанавливает высоту блочных элементов
- ***border***: 5px solid black - позволяет установить толщину, стиль и цвет границы вокруг элемента.
- ***background***: #000 - позволяет установить характеристики фона
