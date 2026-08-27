---
title: "TextBuilder.AppendParagraph"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextBuilder. Добавляет текстовый абзац на страницу Pdf."
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

Добавляет абзац текста на страницу Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textParagraph | TextParagraph | Объект текстового абзаца. |

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

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


