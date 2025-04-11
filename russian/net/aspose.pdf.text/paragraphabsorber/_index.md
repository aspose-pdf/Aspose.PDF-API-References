---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.ParagraphAbsorber. Представляет объект-абсорбер структурных объектов страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, которые описывают его в текстовом координатном пространстве. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции TextFragments, сгруппированные по структурным элементам.
type: docs
weight: 10670
url: /ru/net/aspose.pdf.text/paragraphabsorber/
---
## Класс ParagraphAbsorber

Представляет объект-абсорбер структурных объектов страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, которые описывают его в текстовом координатном пространстве. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через !:TextFragments, сгруппированные по структурным элементам.

```csharp
public class ParagraphAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск секций/абзацев документа или страницы. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск секций/абзацев документа или страницы. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск секций/абзацев документа или страницы с указанными параметрами. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск секций/абзацев документа или страницы с указанными параметрами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Получает или задает значение, указывающее, могут ли начальные текстовые строки следующей секции рассматриваться как продолжение последнего абзаца предыдущей секции. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Получает коллекцию [`PageMarkup`](../pagemarkup/), которые были абсорбированы. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Получает или задает параметры ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Получает или задает значение, которое указывает, сколько раз будут выполняться последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска для горизонтально разделенных секций (заголовки, абзацы и т. д.) и три поиска для вертикально разделенных (колонки). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Получает или задает параметры TextReplaceOptions. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Выполняет поиск секций и абзацев в указанном [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Выполняет поиск на указанной [`Page`](../../aspose.pdf/page/). |

## Замечания

Когда поиск завершен, коллекция [`PageMarkups`](./pagemarkups/) будет содержать объекты [`PageMarkup`](../pagemarkup/), которые представляют структуру страницы через коллекции [`MarkupSection`](../markupsection/) и [`MarkupParagraph`](../markupparagraph/). Объект [`TextFragment`](../textfragment/) предоставляет доступ к тексту, найденному в результате поиска, свойствам текста и позволяет редактировать текст и изменять его состояние (шрифт, размер шрифта, цвет и т. д.).

## Примеры

Пример демонстрирует, как найти первый текстовый сегмент каждого абзаца на первой странице PDF-документа и выделить его.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)