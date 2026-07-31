---
title: "TextSegment.TextSegment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Konstruktor TextSegment. Membuat objek TextSegment"
type: docs
weight: 10
url: /id/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Membuat objek TextSegment.

```csharp
public TextSegment()
```

## Contoh

Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf.

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

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Membuat objek TextSegment.

```csharp
public TextSegment(string text)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | String | Teks segmen. |

## Contoh

Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf.

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
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// buat objek TextBuilder
TextBuilder builder = new TextBuilder(page);

// tambahkan fragmen teks ke halaman Pdf
builder.AppendText(tf);

//simpan dokumen
doc.Save(outFile);
```

### Lihat Juga

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


