---
title: "Kelas TextParagraph"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Text.TextParagraph class. Mewakili paragraf teks sebagai objek teks multiline."
type: docs
weight: 11170
url: /id/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Mewakili paragraf teks sebagai objek teks multiline.

```csharp
public sealed class TextParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextParagraph](textparagraph/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Mendapatkan atau mengatur opsi format. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal untuk teks di dalam [`Rectangle`](./rectangle/) paragraf. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Mendapatkan atau mengatur nilai apakah teks diratakan penuh. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Mendapatkan atau mengatur padding. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Mendapatkan atau mengatur posisi paragraf. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Mendapatkan atau mengatur rectangle paragraf. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Mendapatkan rectangle teks yang ditempatkan ke paragraf. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal untuk teks di dalam [`Rectangle`](./rectangle/) paragraf. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Menambahkan baris teks |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Menambahkan baris teks dengan parameter status teks. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Menambahkan baris teks. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Menambahkan baris teks dengan parameter status teks. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Menambahkan baris teks dengan parameter status teks. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Menambahkan baris teks dengan parameter status teks |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Menambahkan baris teks dengan parameter status teks |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | Memulai penyuntingan TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | Mengakhiri penyuntingan TextParagraph. |

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

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


