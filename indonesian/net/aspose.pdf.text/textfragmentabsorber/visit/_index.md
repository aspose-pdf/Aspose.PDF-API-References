---
title: "TextFragmentAbsorber.Visit"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextFragmentAbsorber. Melakukan pencarian pada halaman yang ditentukan"
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
| halaman | Halaman | Objek halaman PDF document. |

## Contoh

Contoh ini menunjukkan cara menemukan teks pada page pertama document PDF dan mengganti teks tersebut.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
absorber.Visit(doc.Pages[1]);

// Ubah teks pada semua hasil pencarian
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
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
| pdf | Document | Objek PDF document. |

## Contoh

Contoh ini menunjukkan cara menemukan teks pada PDF document dan mengganti teks pada semua hasil pencarian.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
absorber.Visit(doc);

// Ubah teks pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Melakukan pencarian pada objek form yang ditentukan.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xForm | XForm | Objek formulir Pdf. |

### Lihat Juga

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


