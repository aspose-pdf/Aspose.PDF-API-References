---
title: "TextBuilder.AppendParagraph"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextBuilder. Menambahkan paragraf teks ke halaman Pdf."
type: docs
weight: 20
url: /id/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

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

// buat paragraf teks
TextParagraph paragraph = new TextParagraph();
           
// atur persegi panjang paragraf
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// atur opsi pembungkus kata
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// tambahkan baris string
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// tambahkan paragraf ke halaman Pdf dengan TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// simpan dokumen Pdf
doc.Save(outFile);
```

### Lihat Juga

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


