---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextBuilder. يضيف فقرة نصية إلى صفحة Pdf
type: docs
weight: 20
url: /ar/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## طريقة TextBuilder.AppendParagraph

يضيف فقرة نصية إلى صفحة Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| textParagraph | TextParagraph | كائن فقرة نصية. |

## أمثلة

توضح المثال كيفية إنشاء كائن فقرة نصية وإضافته إلى صفحة Pdf.

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

### انظر أيضًا

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)