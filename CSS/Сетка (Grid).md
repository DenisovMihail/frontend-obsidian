## 🧮 3. Grid

**Описание:**  
CSS Grid — это мощная модель сеточной раскладки для создания двумерных макетов, позволяющая точно размещать элементы по строкам и колонкам внутри контейнера с `display: grid` или `inline-grid`.

---
### Таблица:

|Свойство|Для чего используется|Условие применения|Все возможные значения|
|---|---|---|---|
|`grid-template-columns`|Определяет структуру колонок сетки|Применяется к grid-контейнерам|`<track-list>` (например, `100px 1fr auto repeat(3, 50px)`)|
|`grid-template-rows`|Определяет структуру строк сетки|Применяется к grid-контейнерам|`<track-list>` (аналогично колонкам)|
|`grid-template-areas`|Определяет именованные области сетки|Применяется к grid-контейнерам|Строки с именами областей в кавычках, например: `"header header" "sidebar content"`|
|`grid-template`|Сокращённое свойство для колонок, строк и областей|Применяется к grid-контейнерам|Комбинация значений для `grid-template-rows`, `grid-template-columns`, `grid-template-areas`|
|`grid-auto-columns`|Размер колонок, создаваемых автоматически|Применяется к grid-контейнерам|`<track-size>` (например, `auto`, `1fr`, `100px`)|
|`grid-auto-rows`|Размер строк, создаваемых автоматически|Применяется к grid-контейнерам|`<track-size>`|
|`grid-auto-flow`|Определяет способ автоматического размещения элементов|Применяется к grid-контейнерам|`row`, `column`, `row dense`, `column dense`|
|`gap`|Отступы между строками и колонками|Применяется к grid-контейнерам|`<длина>`, `<процент>`|
|`row-gap`|Вертикальные отступы между строками|Применяется к grid-контейнерам|`<длина>`, `<процент>`|
|`column-gap`|Горизонтальные отступы между колонками|Применяется к grid-контейнерам|`<длина>`, `<процент>`|
|`justify-items`|Выравнивание элементов внутри ячеек по горизонтали|Применяется к grid-контейнерам|`start`, `end`, `center`, `stretch`|
|`align-items`|Выравнивание элементов внутри ячеек по вертикали|Применяется к grid-контейнерам|`start`, `end`, `center`, `stretch`|
|`place-items`|Сокращённое для `align-items` и `justify-items`|Применяется к grid-контейнерам|`<align-items> <justify-items>` (например, `center stretch`)|
|`justify-content`|Выравнивание всей сетки по горизонтали|Применяется к grid-контейнерам|`start`, `end`, `center`, `stretch`, `space-between`, `space-around`, `space-evenly`|
|`align-content`|Выравнивание всей сетки по вертикали|Применяется к grid-контейнерам|`start`, `end`, `center`, `stretch`, `space-between`, `space-around`, `space-evenly`|
|`place-content`|Сокращённое для `align-content` и `justify-content`|Применяется к grid-контейнерам|`<align-content> <justify-content>`|
|`grid-column-start`|Начальная линия сетки по горизонтали|Применяется к grid-элементам|`<grid-line>`, `auto`|
|`grid-column-end`|Конечная линия сетки по горизонтали|Применяется к grid-элементам|`<grid-line>`, `auto`|
|`grid-row-start`|Начальная линия сетки по вертикали|Применяется к grid-элементам|`<grid-line>`, `auto`|
|`grid-row-end`|Конечная линия сетки по вертикали|Применяется к grid-элементам|`<grid-line>`, `auto`|
|`grid-column`|Сокращённое для `grid-column-start` и `grid-column-end`|Применяется к grid-элементам|`<start-line> / <end-line>`|
|`grid-row`|Сокращённое для `grid-row-start` и `grid-row-end`|Применяется к grid-элементам|`<start-line> / <end-line>`|
|`grid-area`|Определяет позицию и размер элемента (сокращённое)|Применяется к grid-элементам|`<grid-row-start> / <grid-column-start> / <grid-row-end> / <grid-column-end>` или имя области|
|`justify-self`|Выравнивание элемента внутри ячейки по горизонтали|Применяется к grid-элементам|`auto`, `start`, `end`, `center`, `stretch`|
|`align-self`|Выравнивание элемента внутри ячейки по вертикали|Применяется к grid-элементам|`auto`, `start`, `end`, `center`, `stretch`|
|`place-self`|Сокращённое для `align-self` и `justify-self`|Применяется к grid-элементам|`<align-self> <justify-self>`|