Научиться учиться

Работа по теме "Статическая верстка".

использованны относительные пути к файлам.

Выполненно по методалогиии БЭМ.
для всех свойств выставлен margin: 0 в первой строчке т.к. файл normalize.css не сбрасывает абсолютно все отступы.
используется flex для центрирования эллементов на странице и выставления блоков по сетке в некоторых секциях,
за исключением случаев когда в брифе разрешенно делать абсолютное позиционирование.
каждой секции задан   box-sizing: border-box;

1. в файле index.css хранятся все подключенные стили для каждого блока и элемента, а также подключены шрифты и файл normalize.css.

2. в блоке page объявленны основные шрифты для страницы: 'Inter', Arial, sans-serif;

3. в блоке video перенес изначальные свойства iframe в файл video__iframe.css, валидатор выдает ошибку т.к. в html файле были оставленны свойства allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen


