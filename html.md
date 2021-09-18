# Шпаргалки web

## HTML5 все теги

### Каркас HTML документа по версии HTML5

```html
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8" />
<title>Документ без названия</title>
</head>
<body>
Контент
</body>
</html>
```

Всем тегам HTML в браузерах, по умолчанию, присвоено свойство display:, результатом чего существует разделение элементов на блочные и встроенные или строчные.

## Служебные теги

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;!DOCTYPE> |	Определяет тип документа |	none |
| &lt;head>&lt;/head> |	Контейнер в начале страницы для служебных тегов и подгружаемых функций |	none |
| &lt;title>&lt;/title> |	Заголовок документа отображаемый во вкладке браузера |	none |
| &lt;meta> |	Метаданные страницы |	none |
| &lt;link> |	Подключает внешние сервисы и таблицы стилей |	none |
| &lt;script>&lt;/script> |	Подключает скрипты к станице |	none |
| &lt;style>&lt;/style> |	Подключает глобальные стили к странице |	none |
| &lt;base> |	Базовый URL-адрес — домен |	none |
| &lt;noscript>&lt;/noscrip> |	Блок не поддерживающий скрипты |	block |

## Структурные блоки

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;body>&lt;/body> |	Тело html документа |	block |
| &lt;main>&lt;main> |	Контейнер для всего содержимого страницы |	block |
| &lt;nav>&lt;/nav> |	Контейнер для навигационного меню |	block |
| &lt;header>&lt;header> |	Шапка сайта |	block |
| &lt;article>&lt;/article> |	Блок основного контента, обычно статья |	block |
| &lt;section>&lt;/section> |	Часть контента с заголовком |	block |
| &lt;aside>&lt;/aside> |	Часть контента, имеющая косвенное отношение к основному |	block |
| &lt;footer>&lt;/footer> |	Подвал страницы |	block |
| &lt;div> |	Применяется для создания блочных контейнеров |	block |
| &lt;span>&lt;/span> |	Применяется для создания встроенных контейнеров |	block |
| &lt;figure>&lt;/figure> |	Независимый контейнер. Преимущественно для изображений |	block |
| &lt;figcaption>&lt;/figcaption> |	Заголовок для figure |	block |
| &lt;details>&lt;/details> |	Контейнер с дополнительной информацией, который можно свернуть или развернуть |	block |
| &lt;summary>&lt;/summary> |	Заголовок для details, по которому можно щёлкать, чтоб свернуть или развернуть блок |	block |

## Текст

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;h1>&lt;/h1>…&lt;h6>&lt;/h6> |	Заголовки шесть уровней |	block |
| &lt;p>&lt;/p> |	Абзац |	block |
| &lt;br> |	Перенос строки |	block |
| &lt;wbr> |	Возможное место разрыва строки |	none |
| &lt;hr> |	Прямая линия |	none |
| &lt;blockquote>&lt;/blockquote> |	Цитата |	block |
| &lt;q>&lt;/q> |	Краткая цитата |	inline |
| &lt;cite>&lt;/cite> |	Источник цитирования |	inline |
| &lt;code>&lt;/code> |	Фрагмент кода |	inline |
| &lt;pre>&lt;/pre> |	Неформатированнй код |	block |
| &lt;kbd>&lt;/kbd> |	Текст моноширным шрифтом |	inline |
| &lt;samp>&lt;/samp> |	Результат выполнения скрипта |	inline |
| &lt;var>&lt;/var> |	Выделяет переменные из программ |	inline |
| &lt;del>&lt;/del> |	Зачёркнутый текст помечается как удалённый |	inline |
| &lt;s>&lt;/s> |	Зачёркнутый текст |	block |
| &lt;ins>&lt;ins> |	Подчёркивает изменения в тексте |	inline |
| &lt;u>&lt;/u> |	Подчёркнутый текст |	inline |
| &lt;dfn>&lt;/dfn> |	Выделяет термин курсивом |	inline |
| &lt;em>&lt;/em> |	Выделяет курсивом важные фрагменты текста |	inline |
| &lt;i>&lt;/i> |	Выделяет текст курсивом |	inline |
| &lt;strong>&lt;/strong> |	Выделяет важный текст полужирным |	inline |
| &lt;b>&lt;/b> |	Выделяет текст полужирным |	inline |
| &lt;mark>&lt;/mark> |	Выделяет фрагмент текста жёлтым фоном |	inline |
| &lt;small>&lt;/small> |	Уменьшает размер шрифта |	inline |
| &lt;sub>&lt;/sub> |	Подстрочное написание H2O |	inline |
| &lt;sup>&lt;/sup> |	Надстрочное написание R2 |	inline |
| &lt;time>&lt;time> |	Дата, время выпуска статьи |	inline |
| &lt;abbr>&lt;/abbr> |	Аббревиатура |	inline |
| &lt;address>&lt;/address> |	Адрес автора статьи |	inline |
| &lt;bdi>&lt;/bdi> |	Изолирует текст читаемый справа на лево. Применяется в текстах написанных на двух языках |	inline |
| &lt;bdo>&lt;/bdo> |	Задаёт направление написания текста |	inline |
| &lt;ruby>&lt;/ruby> |	Контейнер для Восточно-Азиатских символов |	inline |
| &lt;rp>&lt;/rp> |	Используется для вывода текста в браузерах, которые не поддерживают тег . В остальных браузерах текст, заключенный в контейнер |	none |
| &lt;rt>&lt;/rt> |	Расшифровка символов |	block |

## Таблицы

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;table>&lt;/table> |	Таблица HTML |	table |
| &lt;tr>&lt;/tr> |	Строка таблицы |	table-row |
| &lt;th>&lt;/th> |	Ячейки заголовков столбцов таблицы |	table-cell |
| &lt;td>&lt;/td> |	Ячейки таблицы |	table-cell |
| &lt;thead>&lt;/thead> |	Группа верхних строк таблицы. Применяется для общего оформления |	table-header-group |
| &lt;tfoot>&lt;/tfoot> |	Группа нижних строк таблицы. Применяется для общего оформления |	table-footer-group |
| &lt;tbody>&lt;/tbody> |	Группа строк в середине таблицы. Применяется для общего оформления |	table-row-group |
| &lt;col> |	Выделяет столбец таблицы |	table-column |
| &lt;colgroup>&lt;/colgroup> |	Группирует несколько столбцов таблицы для общего оформления |	table-column-group |
| &lt;caption>&lt;/caption> |	Описание таблицы |	table-caption

## Списки

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;ol>&lt;/ol> |	Упорядоченный нумерованный список |	block |
| &lt;ul>&lt;/ul> |	Маркированный список |	block |
| &lt;li>&lt;/li> |	Элемент списка |	list-item |
| &lt;dl>&lt;/dl> |	Список с описаниями |	block
| &lt;dt>&lt;/dt> |	Строка списка с описаниями |	block |
| &lt;dd>&lt;/dd> |	Описание строки, списка с описаниями |	block |

## Изображения

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;img> |	Изображение html |	inline |
| &lt;map>&lt;/map> |	Активные области на карте |	inline |
| &lt;area>&lt;/area> |	Активная область с гиперссылкой на карте |	inline |
| &lt;canvas>&lt;/canvas> |	Холст контейнер для динамического отображения изображений созданных с помощью JavaScript |	inline-block |

## Формы HTML

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;form>&lt;/form> |	Формы HTML |	block |
| &lt;input>&lt;/input> |	Многофункциональные поля формы |	inline-block |
| &lt;textarea>&lt;/textarea> |	Многострочное поле формы |	inline-block |
| &lt;label>&lt;/label> |	Обычно текст формы |	inline |
| &lt;datalist>&lt;/datalist> |	Создаёт список вариантов, из которых можно сделать выбор. |	none |
| &lt;option>&lt;/option> |	Опция в раскрывающемся списке |	block |
| &lt;optgroup>&lt;/optgroup> |	Контейнер с заголовком для группы &lt;option> |	block |
| &lt;select>&lt;/select> |	Контейнер для создания раскрывающегося списка |	inline-block |
| &lt;fieldset>&lt;/fieldset> |	Группирует связанные элементы формы |	block |
| &lt;legend>&lt;/legend> |	Заголовок элементов формы, связанных &lt;fieldset> |	block |
| &lt;button>&lt;/button> |	Интерактивная кнопка |	inline-block |
| &lt;keygen>&lt;/keygen> |	Генератор ключей |	inline-block |
| &lt;progress>&lt;/progress> |	Отображает процесс выполнения в числовых значениях |	inline-block |
| &lt;meter>&lt;/meter> |	Используется для отображения числовых значений таких показателей как количество посетителей, величина давления и т.п. |	inline-block |
| &lt;output>&lt;/output> |	Поле для вывода результатов вычислений |	inline |

## Встраиваемые элементы

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;audio>&lt;/audio> |	Аудио файл |	inline-block |
| &lt;video>&lt;/video> |	Видео файл |	inline-block |
| &lt;source>&lt;/source> |	указывает местоположение и тип альтернативных файлов для &lt;video> и &lt;audio> |	none |
| &lt;track>&lt;/track> |	Субтитры |	none |
| &lt;embed>&lt;/embed> |	Встроенный внешний элемент |	inline-block |
| &lt;object>&lt;/object> |	Контейнер для встраиваемого внешнего элемента |	inline-block |
| &lt;param> |	Параметры встраиваемого внешнего элемента |	none |
| &lt;iframe>&lt;/iframe> |	Встроенный фрейм |	block |

## Ссылка

| Синтаксис |	Описание |	display |
| --- | --- | --- |
| &lt;a>&lt;/a> |	Гипер ссылка |	inline |
