---
title: "Aspose.Pdf.Text"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Пространство имен Aspose.Pdf.Text предоставляет классы, позволяющие извлекать текст, добавлять текст, манипулировать существующим текстом документа. Оно также содержит классы, позволяющие извлекать, заменять и подставлять шрифты документа."
type: docs
weight: 250
url: /ru/net/aspose.pdf.text/
---
Пространство имен **Aspose.Pdf.Text** предоставляет классы, позволяющие извлекать текст, добавлять текст, изменять существующий текст Document. Оно также содержит классы, позволяющие извлекать, заменять, подменять шрифты Document.

## Классы

| Класс | Описание |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Представляет ячейку таблицы, существующей на странице. |
| [AbsorbedRow](./absorbedrow/) | Представляет строку таблицы, существующей на странице. |
| [AbsorbedTable](./absorbedtable/) | Представляет таблицу, существующую на странице. |
| [CharInfo](./charinfo/) | Представляет объект информации о символе. Предоставляет данные о позиционировании символа. |
| [CharInfoCollection](./charinfocollection/) | Представляет коллекцию объектов CharInfo. |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | Представляет базовый класс для пользовательской стратегии замены шрифтов. |
| [FileFontSource](./filefontsource/) | Представляет отдельный источник файлов шрифтов. |
| [FolderFontSource](./folderfontsource/) | Представляет папку, содержащую файлы шрифтов. |
| [Font](./font/) | Представляет объект шрифта. |
| [FontAbsorber](./fontabsorber/) | Представляет объект-абсорбер шрифтов. Выполняет поиск шрифтов и предоставляет доступ к результатам поиска через коллекцию [`Fonts`](../aspose.pdf.text/fontabsorber/fonts/). |
| [FontCollection](./fontcollection/) | Представляет коллекцию шрифтов. |
| [FontRepository](./fontrepository/) | Выполняет поиск шрифтов. Ищет среди системно установленных шрифтов и стандартных PDF‑шрифтов. Также предоставляет возможность открывать пользовательские шрифты. |
| [FontSource](./fontsource/) | Представляет базовый класс для источника шрифтов. |
| [FontSourceCollection](./fontsourcecollection/) | Представляет коллекцию источников шрифтов. |
| [FontSubstitution](./fontsubstitution/) | Представляет базовый класс для стратегий замены шрифтов. |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | Представляет коллекцию стратегий замены шрифтов. |
| [MarkupParagraph](./markupparagraph/) | Представляет абзац. |
| [MarkupSection](./markupsection/) | Представляет секцию разметки — прямоугольную область страницы, содержащую текст и визуально отделяемую от других блоков текста. |
| [MemoryFontSource](./memoryfontsource/) | Представляет отдельный источник файлов шрифтов. |
| [PageMarkup](./pagemarkup/) | Разметка страницы представлена коллекциями [`MarkupSection`](../aspose.pdf.text/markupsection/) и [`MarkupParagraph`](../aspose.pdf.text/markupparagraph/). |
| [ParagraphAbsorber](./paragraphabsorber/) | Представляет объект-абсорбер объектов структуры страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции !:TextFragments, сгруппированные по структурным элементам. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Представляет параметры для [`ParagraphAbsorber`](../aspose.pdf.text/paragraphabsorber/). |
| [Position](./position/) | Представляет объект позиции |
| [RegexManager](./regexmanager/) | Предоставляет оболочку для операций с регулярными выражениями с настраиваемыми параметрами тайм‑аута. |
| [SimpleFontSubstitution](./simplefontsubstitution/) | Представляет класс для простой стратегии замены шрифтов. |
| [SystemFontSource](./systemfontsource/) | Представляет все шрифты, установленные в системе. |
| [SystemFontsSubstitution](./systemfontssubstitution/) | Представляет класс стратегии замены шрифтов, заменяющий шрифты на системные шрифты. |
| [TableAbsorber](./tableabsorber/) | Представляет объект‑поглотитель элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [`TableList`](../aspose.pdf.text/tableabsorber/tablelist/). |
| [TabStop](./tabstop/) | Представляет пользовательскую позицию табуляции в абзаце. |
| [TabStops](./tabstops/) | Представляет коллекцию объектов [`TabStop`](../aspose.pdf.text/tabstop/). |
| [TextAbsorber](./textabsorber/) | Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [`Text`](../aspose.pdf.text/textabsorber/text/). |
| [TextBuilder](./textbuilder/) | Добавляет объект текста на страницу PDF. |
| [TextEditOptions](./texteditoptions/) | Описывает параметры операций редактирования текста. |
| [TextExtractionError](./textextractionerror/) | Описывает ошибку извлечения текста, возникшую в документе PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Представляет место в документе PDF, где возникла ошибка извлечения текста. |
| [TextExtractionOptions](./textextractionoptions/) | Представляет параметры извлечения текста |
| [TextFormattingOptions](./textformattingoptions/) | Представляет параметры форматирования текста |
| [TextFragment](./textfragment/) | Представляет фрагмент текста PDF. |
| [TextFragmentAbsorber](./textfragmentabsorber/) | Представляет объект‑поглотитель фрагментов текста. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../aspose.pdf.text/textfragmentabsorber/textfragments/). |
| [TextFragmentCollection](./textfragmentcollection/) | Представляет коллекцию фрагментов текста |
| [TextFragmentState](./textfragmentstate/) | Представляет состояние текста фрагмента. |
| [TextOptions](./textoptions/) | Представляет параметры обработки текста |
| [TextParagraph](./textparagraph/) | Представляет абзацы текста как многострочный объект текста. |
| [TextReplaceOptions](./textreplaceoptions/) | Представляет параметры замены текста |
| [TextSearchOptions](./textsearchoptions/) | Представляет параметры поиска текста |
| [TextSegment](./textsegment/) | Представляет сегмент текста PDF. |
| [TextSegmentCollection](./textsegmentcollection/) | Представляет коллекцию сегментов текста |
| [TextState](./textstate/) | Представляет состояние текста |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IFontOptions](./ifontoptions/) | Полезные свойства для настройки поведения шрифта |
| [ITableElement](./itableelement/) | Этот интерфейс представляет элемент существующей таблицы, извлечённый с помощью TableAbsorber. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | Перечисление Text CoordinateOrigin. |
| [FontStyles](./fontstyles/) | Указывает информацию о стиле, применяемую к тексту. |
| [FontTypes](./fonttypes/) | Перечисление поддерживаемых типов шрифтов. |
| [SubstitutionFontCategories](./substitutionfontcategories/) | Представляет категории шрифтов, которые могут быть заменены. |
| [TabAlignmentType](./tabalignmenttype/) | Перечисляет типы выравнивания табуляции. |
| [TabLeaderType](./tableadertype/) | Перечисляет типы лидеров табуляции. |
| [TextRenderingMode](./textrenderingmode/) | Режим отображения текста, Tmode, определяет, будет ли отображение текста вызывать обводку контуров глифов, их заполнение, использование в качестве границы обрезки или комбинацию этих трёх вариантов. |


