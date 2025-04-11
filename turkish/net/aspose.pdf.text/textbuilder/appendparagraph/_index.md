---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder metodu. Pdf sayfasına metin paragrafı ekler
type: docs
weight: 20
url: /tr/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph metodu

Pdf sayfasına metin paragrafı ekler.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textParagraph | TextParagraph | Metin paragrafı nesnesi. |

## Örnekler

Örnek, metin paragrafı nesnesi oluşturmayı ve bunu Pdf sayfasına eklemeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextParagraph](../../textparagraph/)
* sınıf [TextBuilder](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)