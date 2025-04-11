---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.FontRepository. Melakukan pencarian font. Mencari di font yang terinstal di sistem dan font Pdf standar. Juga menyediakan fungsionalitas untuk membuka font kustom
type: docs
weight: 10540
url: /id/net/aspose.pdf.text/fontrepository/
---
## Kelas FontRepository

Melakukan pencarian font. Mencari di font yang terinstal di sistem dan font Pdf standar. Juga menyediakan fungsionalitas untuk membuka font kustom.

```csharp
public sealed class FontRepository
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FontRepository](fontrepository/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Mendapatkan koleksi sumber font. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Mendapatkan koleksi strategi substitusi font. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Mencari dan mengembalikan font dengan nama font yang ditentukan. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Mencari dan mengembalikan font dengan nama font yang ditentukan mengabaikan atau menghormati sensitivitas huruf besar/kecil. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan mengabaikan atau menghormati sensitivitas huruf besar/kecil. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Memuat font yang terinstal di sistem dan font Pdf standar. Metode ini dirancang untuk mempercepat proses pemuatan font. Secara default, font dimuat pada permintaan pertama untuk font apa pun. Penggunaan metode ini memuat font sistem dan font Pdf standar segera sebelum dokumen Pdf dibuka. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Membuka font dengan jalur file font yang ditentukan. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Membuka font dengan aliran font yang ditentukan. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Membuka font dengan jalur file font yang ditentukan dan jalur file metrik. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Memuat ulang semua font yang ditentukan oleh properti [`Sources`](./sources/) |

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks di halaman pertama.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../textfragmentabsorber/)
* kelas [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)