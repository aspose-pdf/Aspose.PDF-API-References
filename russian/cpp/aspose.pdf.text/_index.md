---
title: "Пространство имён Aspose::Pdf::Text"
linktitle: "Aspose::Pdf::Text"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать пространство имён Aspose::Pdf::Text в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.text/
---



## Классы

| Класс | Описание |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Представляет ячейку таблицы, существующую на странице. |
| [AbsorbedRow](./absorbedrow/) | Представляет строку таблицы, существующую на странице. |
| [AbsorbedTable](./absorbedtable/) | Представляет таблицу, существующую на странице. |
| [CharInfo](./charinfo/) | Представляет объект информации о символе. Предоставляет данные о позиционировании символа. |
| [CharInfoCollection](./charinfocollection/) | Представляет коллекцию объектов [CharInfo](./charinfo/). |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | Представляет базовый класс для пользовательской стратегии замены шрифтов. |
| [FileFontSource](./filefontsource/) | Представляет источник отдельного файла шрифта. |
| [FolderFontSource](./folderfontsource/) | Представляет папку, содержащую файлы шрифтов. |
| [Font](./font/) | Представляет объект шрифта. |
| [FontAbsorber](./fontabsorber/) | Представляет объект-абсорбер шрифтов. Выполняет поиск шрифтов и предоставляет доступ к результатам поиска через коллекцию [FontAbsorber::Fonts](../). |
| [FontCollection](./fontcollection/) | Представляет коллекцию шрифтов. |
| [FontRepository](./fontrepository/) | Выполняет поиск шрифтов. Ищет среди системно установленных шрифтов и стандартных шрифтов [Pdf](../aspose.pdf/). Также предоставляет возможность открывать пользовательские шрифты. |
| [FontSource](./fontsource/) | Представляет базовый класс источника шрифтов. |
| [FontSourceCollection](./fontsourcecollection/) | Представляет коллекцию источников шрифтов. |
| [FontSubstitution](./fontsubstitution/) | Представляет базовый класс стратегий замены шрифтов. |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | Представляет коллекцию стратегий замены шрифтов. |
| [IFontOptions](./ifontoptions/) | Полезные свойства для настройки поведения [Font](./font/). |
| [IFontSubstitutionCallback](./ifontsubstitutioncallback/) | Этот интерфейс объявляет механизм обратного вызова для отправки уведомлений. |
| [IFontSubstitutionRegistrator](./ifontsubstitutionregistrator/) | Этот интерфейс объявляет необходимый функционал для регистрации замен шрифтов. |
| [ITableElement](./itableelement/) | Этот интерфейс представляет элемент существующей таблицы, извлечённый с помощью [TableAbsorber](./tableabsorber/). |
| [MarkupParagraph](./markupparagraph/) | Представляет абзац. |
| [MarkupSection](./markupsection/) | Представляет секцию разметки — прямоугольную область страницы, содержащую текст и визуально отделяемую от других блоков текста. |
| [MemoryFontSource](./memoryfontsource/) | Представляет источник отдельного файла шрифта. |
| [OnSegmentChangedEventArgs](./onsegmentchangedeventargs/) | Содержит дополнительную информацию о событии OnSegmentChangedEvent, которое доставляется слушателям. |
| [PageMarkup](./pagemarkup/) | Разметка [Page](../aspose.pdf/page/) представлена коллекциями [MarkupSection](./markupsection/) и [MarkupParagraph](./markupparagraph/). |
| [ParagraphAbsorber](./paragraphabsorber/) | Представляет объект-абсорбер структурных объектов страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции [TextFragments](../), сгруппированные по структурным элементам. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Представляет параметры для [ParagraphAbsorber](./paragraphabsorber/). |
| [Position](./position/) | Представляет объект позиции. |
| [RegexManager](./regexmanager/) | Предоставляет оболочку для операций с регулярными выражениями с настраиваемыми параметрами таймаута. |
| [SimpleFontSubstitution](./simplefontsubstitution/) | Представляет класс простой стратегии замены шрифтов. |
| [SystemFontSource](./systemfontsource/) | Представляет все шрифты, установленные в системе. |
| [SystemFontsSubstitution](./systemfontssubstitution/) | Представляет класс стратегии замены шрифтов, заменяющей шрифты на системные. |
| [TableAbsorber](./tableabsorber/) | Представляет объект-абсорбер элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [TableAbsorber::TableList](../). |
| [TabStop](./tabstop/) | Представляет пользовательскую позицию табуляции в абзаце. |
| [TabStops](./tabstops/) | Представляет коллекцию объектов [TabStop](./tabstop/). |
| [TextAbsorber](./textabsorber/) | Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [TextAbsorber::Text](../). |
| [TextBuilder](./textbuilder/) | Добавляет объект текста на страницу [Pdf](../aspose.pdf/). |
| [TextEditOptions](./texteditoptions/) | Описывает параметры операций редактирования текста. |
| [TextExtractionError](./textextractionerror/) | Описывает ошибку извлечения текста, возникшую в PDF‑документе. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Представляет место в PDF‑документе, где возникла ошибка извлечения текста. |
| [TextExtractionOptions](./textextractionoptions/) | Представляет параметры извлечения текста. |
| [TextFormattingOptions](./textformattingoptions/) | Представляет параметры форматирования текста. |
| [TextFragment](./textfragment/) | Представляет фрагмент текста [Pdf](../aspose.pdf/). |
| [TextFragmentAbsorber](./textfragmentabsorber/) | Представляет объект‑поглотитель фрагментов текста. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../). |
| [TextFragmentCollection](./textfragmentcollection/) | Представляет коллекцию фрагментов текста. |
| [TextFragmentState](./textfragmentstate/) | Представляет состояние текста фрагмента. |
| [TextOptions](./textoptions/) | Представляет параметры обработки текста. |
| [TextParagraph](./textparagraph/) | Представляет абзацы текста как многострочный объект текста. |
| [TextReplaceOptions](./textreplaceoptions/) | Представляет параметры замены текста. |
| [TextSearchOptions](./textsearchoptions/) | Представляет параметры поиска текста. |
| [TextSegment](./textsegment/) | Представляет сегмент текста [Pdf](../aspose.pdf/). |
| [TextSegmentCollection](./textsegmentcollection/) | Представляет коллекцию сегментов текста. |
| [TextState](./textstate/) | Представляет состояние текста. |
| [UnicodeSubstitution](./unicodesubstitution/) | Представляет замену кодов символов. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | Перечисление [Text](./)[CoordinateOrigin](./coordinateorigin/). |
| [FontStyles](./fontstyles/) | Указывает информацию о стиле, применяемую к тексту. |
| [FontTypes](./fonttypes/) | Перечисление поддерживаемых типов шрифтов. |
| [SubstitutionFontCategories](./substitutionfontcategories/) | Представляет категории шрифтов, которые могут быть заменены. |
| [TabAlignmentType](./tabalignmenttype/) | Перечисляет типы выравнивания табуляции. |
| [TabLeaderType](./tableadertype/) | Перечисляет типы табуляционных лидеров. |
| [TextRenderingMode](./textrenderingmode/) | Режим отображения текста, Tmode, определяет, будет ли отображение текста вызывать обводку контуров глифов, их заполнение, использование в качестве границы обрезки или любую комбинацию этих трёх вариантов. |
