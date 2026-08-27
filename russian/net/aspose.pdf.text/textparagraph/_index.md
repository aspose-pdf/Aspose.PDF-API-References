---
title: "Класс TextParagraph"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TextParagraph. Представляет текстовые абзацы как многострочный текстовый объект"
type: docs
weight: 11170
url: /ru/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Представляет абзацы текста как многострочный объект текста.

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
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Получает или задаёт значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Получает или задаёт параметры форматирования. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание текста внутри [`Rectangle`](./rectangle/) абзаца. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Получает или задаёт значение, указывающее, выровнен ли текст по ширине. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Получает или задаёт отступ. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Получает или задаёт позицию абзаца. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Получает или задаёт прямоугольник абзаца. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Получает или задаёт угол поворота в градусах. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Получает или задаёт значение отступа последующих строк. Если установить ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Получает прямоугольник текста, размещённого в абзаце. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Получает или задаёт вертикальное выравнивание текста внутри [`Rectangle`](./rectangle/) абзаца. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Добавляет строку текста |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Добавляет строку текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Добавляет строку текста с параметрами состояния текста. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Добавляет строку текста с параметрами состояния текста |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Добавляет строку текста с параметрами состояния текста |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Начинает редактирование TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Завершает редактирование TextParagraph. |

## Примеры

В примере демонстрируется, как создать объект текстового абзаца и добавить его на страницу PDF.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// создать текстовый абзац
TextParagraph paragraph = new TextParagraph();
           
// установить прямоугольник абзаца
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// установить параметры переноса слов
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// добавить строки текста
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// добавить абзац на страницу PDF с помощью TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// сохранить документ PDF
doc.Save(outFile);
```

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


