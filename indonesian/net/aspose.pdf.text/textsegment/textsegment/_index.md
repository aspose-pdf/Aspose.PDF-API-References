---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor TextSegment. Membuat objek TextSegment
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

Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks dan melampirkannya ke halaman Pdf.

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

* kelas [TextSegment](../)
* ruang nama [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Membuat objek TextSegment.

```csharp
public TextSegment(string text)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | String | Teks segmen teks. |

## Contoh

Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks dan melampirkannya ke halaman Pdf.

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
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### Lihat Juga

* kelas [TextSegment](../)
* ruang nama [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)