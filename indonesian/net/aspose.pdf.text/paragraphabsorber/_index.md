---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.ParagraphAbsorber. Mewakili objek penyerap dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks dan menyediakan akses untuk persegi panjang dan poligon yang mendeskripsikannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi TextFragments yang dikelompokkan berdasarkan elemen struktur
type: docs
weight: 10670
url: /id/net/aspose.pdf.text/paragraphabsorber/
---
## Kelas ParagraphAbsorber

Mewakili objek penyerap dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks dan menyediakan akses untuk persegi panjang dan poligon yang mendeskripsikannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi !:TextFragments yang dikelompokkan berdasarkan elemen struktur.

```csharp
public class ParagraphAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman dengan parameter yang ditentukan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman dengan parameter yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah baris teks yang dimulai dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir dari bagian sebelumnya. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Mendapatkan koleksi [`PageMarkup`](../pagemarkup/) yang telah diserap. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Mendapatkan atau menetapkan ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Mendapatkan atau menetapkan nilai yang menginstruksikan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Ini berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk yang dibagi secara vertikal (kolom). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Mendapatkan atau menetapkan TextReplaceOptions. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Melakukan pencarian untuk bagian dan paragraf pada [`Document`](../../aspose.pdf/document/) yang ditentukan. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Melakukan pencarian pada [`Page`](../../aspose.pdf/page/) yang ditentukan. |

## Catatan

Ketika pencarian selesai, koleksi [`PageMarkups`](./pagemarkups/) akan berisi objek [`PageMarkup`](../pagemarkup/) yang mewakili struktur halaman melalui koleksi [`MarkupSection`](../markupsection/) dan [`MarkupParagraph`](../markupparagraph/). Objek [`TextFragment`](../textfragment/) menyediakan akses ke teks kejadian pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah status teks (font, ukuran font, warna, dll).

## Contoh

Contoh ini menunjukkan bagaimana menemukan segmen teks pertama dari setiap paragraf di halaman pertama dokumen PDF dan menyorotnya.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)