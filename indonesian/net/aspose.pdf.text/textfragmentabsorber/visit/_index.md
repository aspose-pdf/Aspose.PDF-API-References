---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metode TextFragmentAbsorber. Melakukan pencarian pada halaman yang ditentukan
type: docs
weight: 150
url: /id/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Melakukan pencarian pada halaman yang ditentukan.

```csharp
public override void Visit(Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Page | Objek halaman dokumen PDF. |

## Contoh

Contoh ini menunjukkan cara menemukan teks di halaman pertama dokumen PDF dan mengganti teks tersebut.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Melakukan pencarian pada dokumen yang ditentukan.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdf | Document | Objek dokumen PDF. |

## Contoh

Contoh ini menunjukkan cara menemukan teks pada dokumen PDF dan mengganti teks dari semua kemunculan pencarian.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Melakukan pencarian pada objek formulir yang ditentukan.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xForm | XForm | Objek formulir PDF. |

### Lihat Juga

* kelas [XForm](../../../aspose.pdf/xform/)
* kelas [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)