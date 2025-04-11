---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TextParagraph. Представляет текстовые абзацы как объект многострочного текста
type: docs
weight: 10990
url: /ru/net/aspose.pdf.text/textparagraph/
---
## Класс TextParagraph

Представляет текстовые абзацы как объект многострочного текста.

```csharp
public sealed class TextParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextParagraph](textparagraph/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Получает или задает значение отступа последующих строк. Если установлено ненулевое значение, оно имеет преимущество над значением FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Получает или задает параметры форматирования. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание текста внутри [`Rectangle`](./rectangle/) абзаца. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Получает или задает значение, указывающее, выровнен ли текст. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Получает или задает отступ. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Получает или задает позицию абзаца. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Получает или задает прямоугольник абзаца. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Получает или задает угол поворота в градусах. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Получает или задает значение отступа последующих строк. Если установлено ненулевое значение, оно имеет преимущество над значением FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Получает прямоугольник текста, размещенного в абзаце. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание текста внутри [`Rectangle`](./rectangle/) абзаца. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Добавляет текстовую строку |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Добавляет текстовую строку. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Добавляет текстовую строку с параметрами состояния текста |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Добавляет текстовую строку с параметрами состояния текста |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Начинает редактирование TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Завершает редактирование TextParagraph. |

## Примеры

Пример демонстрирует, как создать объект текстового абзаца и добавить его на страницу Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)