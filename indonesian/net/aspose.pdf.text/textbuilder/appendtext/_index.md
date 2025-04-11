---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Metode TextBuilder. Menambahkan fragmen teks ke halaman Pdf
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

Contoh ini menunjukkan cara membuat objek fragmen teks, menyesuaikan segmen teksnya dan menambahkannya ke halaman Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [TextFragment](../../textfragment/)
* kelas [TextBuilder](../)
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

* kelas [TextFragment](../../textfragment/)
* kelas [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)