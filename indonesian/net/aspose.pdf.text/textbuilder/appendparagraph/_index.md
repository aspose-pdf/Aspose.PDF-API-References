---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: Metode TextBuilder. Menambahkan paragraf teks ke halaman Pdf
type: docs
weight: 20
url: /id/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## Metode TextBuilder.AppendParagraph

Menambahkan paragraf teks ke halaman Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textParagraph | TextParagraph | Objek paragraf teks. |

## Contoh

Contoh ini menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf.

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

### Lihat Juga

* kelas [TextParagraph](../../textparagraph/)
* kelas [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)