---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Метод TextBuilder. Добавляет текстовый абзац на страницу Pdf
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Метод TextBuilder.AppendParagraph

Добавляет текстовый абзац на страницу Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textParagraph | TextParagraph | Объект текстового абзаца. |

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

* класс [TextParagraph](../../textparagraph/)
* класс [TextBuilder](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)