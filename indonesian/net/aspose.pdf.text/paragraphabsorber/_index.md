---
title: "Kelas ParagraphAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.ParagraphAbsorber. Mewakili objek absorber dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan polydons yang menggambarkannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi TextFragments yang dikelompokkan berdasarkan elemen struktur."
type: docs
weight: 10850
url: /id/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Mewakili objek absorber struktur halaman seperti bagian dan paragraf. Melakukan pencarian bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan poligon yang menggambarkannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi !:TextFragments yang dikelompokkan berdasarkan elemen struktur.

```csharp
public class ParagraphAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dokumen atau halaman. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dokumen atau halaman. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dokumen atau halaman dengan parameter yang ditentukan. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Menginisialisasi instance baru dari `ParagraphAbsorber` yang melakukan pencarian untuk bagian/paragraf dokumen atau halaman dengan parameter yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan paragraf terakhir dari bagian sebelumnya. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Mendapatkan koleksi [`PageMarkup`](../pagemarkup/) yang telah diserap. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Mendapatkan atau mengatur ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Artinya tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Mendapatkan atau mengatur TextReplaceOptions. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Melakukan pencarian untuk bagian dan paragraf pada [`Document`](../../aspose.pdf/document/) yang ditentukan. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Melakukan pencarian pada [`Page`](../../aspose.pdf/page/) yang ditentukan. |

## Catatan

Setelah pencarian selesai, koleksi [`PageMarkups`](./pagemarkups/) akan berisi objek [`PageMarkup`](../pagemarkup/) yang mewakili struktur halaman melalui koleksi [`MarkupSection`](../markupsection/) dan [`MarkupParagraph`](../markupparagraph/). Objek [`TextFragment`](../textfragment/) menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

## Contoh

Contoh ini menunjukkan cara menemukan segmen teks pertama dari setiap paragraf pada halaman pertama dokumen PDF dan menyorotnya.

```csharp
// Buka dokumen
Document doc = new Document("input.pdf");

// Buat objek ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Terima absorber untuk halaman pertama
absorber.Visit(doc.Pages[1]);

// Dapatkan objek markup dari halaman pertama
PageMarkup markup = absorber.PageMarkups[0];

// Iterasi melalui elemen struktur teks halaman untuk menemukan fragmen teks pertama dari setiap paragraf
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Perbarui properti teks
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Simpan dokumen
doc.Save(GetOutputPath("output.pdf"));
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


