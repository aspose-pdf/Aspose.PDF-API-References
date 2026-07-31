---
title: "TextBuilder.AppendText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextBuilder. Menambahkan fragmen teks ke halaman Pdf"
type: docs
weight: 30
url: /id/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Menambahkan fragmen teks ke halaman Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFragment | TextFragment | Objek fragmen teks. |

## Contoh

Contoh ini menunjukkan cara membuat objek fragmen teks, menyesuaikan segmen teksnya, dan menambahkannya ke halaman Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// buat fragmen teks
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// atur properti teksnya
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// tambahkan satu segmen lagi ke koleksi Segments fragmen teks
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// buat objek TextBuilder
TextBuilder builder = new TextBuilder(page);

// tambahkan fragmen teks ke halaman Pdf
builder.AppendText(tf);

//simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Menambahkan daftar fragmen teks ke halaman Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFragments | List`1 | Koleksi fragmen teks |

### Lihat Juga

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


