---
title: Aspose.Pdf.Text
second_title: Aspose.PDF for .NET API Reference
description: Пространство имен Aspose.Pdf.Text предоставляет классы, которые позволяют извлекать текст, добавлять текст, манипулировать существующим текстом документа. Оно также содержит классы, которые позволяют извлекать, заменять, подменять шрифты документа.
type: docs
weight: 260
url: /ru/net/aspose.pdf.text/
---
Пространство имен **Aspose.Pdf.Text** предоставляет классы, которые позволяют извлекать текст, добавлять текст, манипулировать существующим текстом документа. Оно также содержит классы, которые позволяют извлекать, заменять, подменять шрифты документа.

## Классы

| Класс | Описание |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Представляет ячейку таблицы, которая существует на странице |
| [AbsorbedRow](./absorbedrow/) | Представляет строку таблицы, которая существует на странице |
| [AbsorbedTable](./absorbedtable/) | Представляет таблицу, которая существует на странице |
| [CharInfo](./charinfo/) | Представляет объект информации о символе. Предоставляет информацию о позиционировании символов. |
| [CharInfoCollection](./charinfocollection/) | Представляет коллекцию объектов CharInfo. |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | Представляет базовый класс для стратегии подмены шрифтов. |
| [FileFontSource](./filefontsource/) | Представляет источник одного файла шрифта. |
| [FolderFontSource](./folderfontsource/) | Представляет папку, содержащую файлы шрифтов. |
| [Font](./font/) | Представляет объект шрифта. |
| [FontAbsorber](./fontabsorber/) | Представляет объект-абсорбер шрифтов. Выполняет поиск шрифтов и предоставляет доступ к результатам поиска через коллекцию [`Fonts`](../aspose.pdf.text/fontabsorber/fonts/). |
| [FontCollection](./fontcollection/) | Представляет коллекцию шрифтов. |
| [FontRepository](./fontrepository/) | Выполняет поиск шрифтов. Ищет в системных установленных шрифтах и стандартных шрифтах Pdf. Также предоставляет функциональность для открытия пользовательских шрифтов. |
| [FontSource](./fontsource/) | Представляет базовый класс для источника шрифта. |
| [FontSourceCollection](./fontsourcecollection/) | Представляет коллекцию источников шрифтов. |
| [FontSubstitution](./fontsubstitution/) | Представляет базовый класс для стратегий подмены шрифтов. |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | Представляет коллекцию стратегий подмены шрифтов. |
| [MarkupParagraph](./markupparagraph/) | Представляет абзац. |
| [MarkupSection](./markupsection/) | Представляет разметку секции - прямоугольную область страницы, которая содержит текст и может быть визуально отделена от других текстовых блоков. |
| [MemoryFontSource](./memoryfontsource/) | Представляет источник одного файла шрифта. |
| [PageMarkup](./pagemarkup/) | Разметка страницы, представленная коллекциями [`MarkupSection`](../aspose.pdf.text/markupsection/) и [`MarkupParagraph`](../aspose.pdf.text/markupparagraph/). |
| [ParagraphAbsorber](./paragraphabsorber/) | Представляет объект-абсорбер объектов структуры страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, которые описывают их в текстовом координатном пространстве. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции !:TextFragments, сгруппированные по структурным элементам. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Представляет параметры для [`ParagraphAbsorber`](../aspose.pdf.text/paragraphabsorber/). |
| [Position](./position/) | Представляет объект позиции |
| [RegexManager](./regexmanager/) | Предоставляет обертку для операций с регулярными выражениями с настраиваемыми параметрами таймаута. |
| [SimpleFontSubstitution](./simplefontsubstitution/) | Представляет класс для стратегии простой подмены шрифтов. |
| [SystemFontSource](./systemfontsource/) | Представляет все шрифты, установленные в системе. |
| [SystemFontsSubstitution](./systemfontssubstitution/) | Представляет класс для стратегии подмены шрифтов, который заменяет шрифты системными шрифтами. |
| [TableAbsorber](./tableabsorber/) | Представляет объект-абсорбер элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [`TableList`](../aspose.pdf.text/tableabsorber/tablelist/). |
| [TabStop](./tabstop/) | Представляет пользовательскую позицию табуляции в абзаце. |
| [TabStops](./tabstops/) | Представляет коллекцию объектов [`TabStop`](../aspose.pdf.text/tabstop/). |
| [TextAbsorber](./textabsorber/) | Представляет объект-абсорбер текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [`Text`](../aspose.pdf.text/textabsorber/text/). |
| [TextBuilder](./textbuilder/) | Добавляет объект текста на страницу Pdf. |
| [TextEditOptions](./texteditoptions/) | Описывает параметры операций редактирования текста. |
| [TextExtractionError](./textextractionerror/) | Описывает ошибку извлечения текста, которая возникла в документе PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Представляет местоположение в документе PDF, где возникла ошибка извлечения текста. |
| [TextExtractionOptions](./textextractionoptions/) | Представляет параметры извлечения текста |
| [TextFormattingOptions](./textformattingoptions/) | Представляет параметры форматирования текста |
| [TextFragment](./textfragment/) | Представляет фрагмент текста Pdf. |
| [TextFragmentAbsorber](./textfragmentabsorber/) | Представляет объект-абсорбер текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../aspose.pdf.text/textfragmentabsorber/textfragments/). |
| [TextFragmentCollection](./textfragmentcollection/) | Представляет коллекцию текстовых фрагментов |
| [TextFragmentState](./textfragmentstate/) | Представляет состояние текста текстового фрагмента. |
| [TextOptions](./textoptions/) | Представляет параметры обработки текста |
| [TextParagraph](./textparagraph/) | Представляет текстовые абзацы как многострочный текстовый объект. |
| [TextReplaceOptions](./textreplaceoptions/) | Представляет параметры замены текста |
| [TextSearchOptions](./textsearchoptions/) | Представляет параметры поиска текста |
| [TextSegment](./textsegment/) | Представляет сегмент текста Pdf. |
| [TextSegmentCollection](./textsegmentcollection/) | Представляет коллекцию текстовых сегментов |
| [TextState](./textstate/) | Представляет состояние текста текста |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IFontOptions](./ifontoptions/) | Полезные свойства для настройки поведения шрифта |
| [ITableElement](./itableelement/) | Этот интерфейс представляет элемент существующей таблицы, извлеченной с помощью TableAbsorber. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | Перечисление CoordinateOrigin текста. |
| [FontStyles](./fontstyles/) | Указывает информацию о стиле, применяемую к тексту. |
| [FontTypes](./fonttypes/) | Перечисление поддерживаемых типов шрифтов. |
| [SubstitutionFontCategories](./substitutionfontcategories/) | Представляет категории шрифтов, которые могут быть заменены. |
| [TabAlignmentType](./tabalignmenttype/) | Перечисляет типы выравнивания табуляции. |
| [TabLeaderType](./tableadertype/) | Перечисляет типы лидеров табуляции. |
| [TextRenderingMode](./textrenderingmode/) | Режим рендеринга текста, Tmode, определяет, будет ли отображение текста приводить к обводке, заливке, использованию в качестве границы обрезки или к некоторой комбинации из трех. |