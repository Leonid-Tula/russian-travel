# Проект 3: Путешествие по России

### Обзор
* Интро
* Figma
* Описание хода выполнения проекта
* Ссылка на готовый проект
* Планы по доработке

**Интро**

 Проект о путешествии по России.
В Фигме размещён исходный макет, из которого следует, как проект должен выглядеть на самых распространённых разрешениях экранов.

**Figma**

* [Исходная ссылка на макет в Figma](https://www.figma.com/file/OyRWEjU6wBwRe1hapzQoLx/Sprint-3%3A-Russia-%2F-desktop-%2B-mobile?node-id=28503%3A0) 

Вышеуказанная ссылка оказалась нерабочей, для выполнения работы использовалась: 
* [Рабочая ссылка на макет в Figma](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-%2B-mobile?node-id=63326%3A0)

**Описание хода выполнения проекта**

В ходе реализации проекта были применены технологии:
- подключение локальных шрифтов, скачанных из внешнего источника
- использован flex для выравнивания элементов на странице
- использован grid для построения сетки элементов 
- для корректного отображения на различных устройствах использованы @media запросы, подключенных внутри файла модифицируемого блока/ элемента
- структура файлов организованна по БЭМ Nested
- применено наложение элементов друг на друга с использованием свойства background и без него
- использована оптимизация изображений с помощью сервиса https://tinypng.com/, что позволило сэкономить 199Kb или 12% от общего веса картинок
- некоторые размеры схожие до размера в 1px и имеющие признаки схожего применения были приведены к общему размеру, например отступ между блоками place
- к ссылкам и всем интерактивным элементам, кроме логотипа, применено свойство hover
- проект опубликован с помощью github pages

**Ссылка на готовый проект**

* [Ссылка на готовый проект](https://leonid-tula.github.io/russian-travel/)

**Планы по доработке**
* Добавить пару точек перелома, с изменением размера шрифта и верхнего отступа для блока cover, с целью лучшего отображения текста на различных смартфонах 

* Дождаться вердикта ревьюера и исправить все замечания:))

**V0.3**

- Исправлены замечания с пометкой нужно исправить
- Исправлены частично замечания с пометкой можно лучше
- экспортирована с объединением слоёв из figma и оптимизирована картинка блока lead, сэкономлено 499Kb или 71% её веса
- применена технология акцентирования части текста span
- изображение в блоке cover реализовано через background
- устранена ошибка, из-за которой возникали белые поля на больших разрешениях
- применён булевый модификатор для подчёркивания выбранного языка

**Планы по доработке**
- Переработать и добавить точки перелома, с изменением отображения количества колонок, с целью лучшего отображения контента на больших смартфонах и малых планшетах
- задать transition для ссылок