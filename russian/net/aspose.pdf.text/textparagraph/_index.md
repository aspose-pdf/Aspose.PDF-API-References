---
title: TextParagraph
second_title: Aspose.PDF для справочника API .NET
description: Представляет текстовые абзацы как многострочный текстовый объект.
type: docs
weight: 7150
url: /ru/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Представляет текстовые абзацы как многострочный текстовый объект.

```csharp
public sealed class TextParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextParagraph](textparagraph)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent) { get; set; } | Получает или задает значение отступа последующих строк. Если задано ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions) { get; set; } | Получает или задает параметры форматирования. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание текста внутри абзаца.[`Rectangle`](./rectangle) . |
| [Justify](../../aspose.pdf.text/textparagraph/justify) { get; set; } | Получает или задает значение, независимо от того, выравнивается ли текст. |
| [Margin](../../aspose.pdf.text/textparagraph/margin) { get; set; } | Получает или задает заполнение. |
| [Position](../../aspose.pdf.text/textparagraph/position) { get; set; } | Получает или задает положение абзаца. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle) { get; set; } | Получает или задает прямоугольник абзаца. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation) { get; set; } | Получает или задает угол поворота в градусах. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent) { get; set; } | Получает или задает значение отступа последующих строк. Если задано ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle) { get; } | Получает прямоугольник текста, помещенного в абзац. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание текста внутри абзаца.[`Rectangle`](./rectangle) . |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_3)(string) | Добавляет текстовую строку |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline)(TextFragment) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_6)(string, float) | Добавляет текстовую строку. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_4)(string, TextState) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_1)(TextFragment, TextState) | Добавляет текстовую строку с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_5)(string, TextState, float) | Добавляет текстовую строку с текстовыми параметрами состояния |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_2)(TextFragment, TextState, float) | Добавляет текстовую строку с текстовыми параметрами состояния |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit)() | Начинает редактирование TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit)() | Завершает редактирование TextParagraph. |

### Примеры

Пример демонстрирует, как создать объект текстового абзаца и добавить его на страницу Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// создать текстовый абзац
TextParagraph paragraph = new TextParagraph();
           
// устанавливаем прямоугольник абзаца
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// устанавливаем параметры переноса слов
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// добавляем строковые строки
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// добавляем абзац на страницу Pdf с помощью TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// сохранить PDF-документ
doc.Save(outFile);
```

### Смотрите также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->