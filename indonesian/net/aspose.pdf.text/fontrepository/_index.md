---
title: "Kelas FontRepository"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.FontRepository. Melakukan pencarian font. Mencari dalam font yang terpasang di sistem dan font Pdf standar. Juga menyediakan fungsionalitas untuk membuka font khusus"
type: docs
weight: 10720
url: /id/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Melakukan pencarian font. Mencari dalam font yang terpasang di sistem dan font Pdf standar. Juga menyediakan fungsionalitas untuk membuka font khusus.

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
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Memuat font yang diinstal di sistem dan font Pdf standar. Metode ini dirancang untuk mempercepat proses pemuatan font. Secara default, font dimuat pada permintaan pertama untuk font apa pun. Penggunaan metode ini memuat font sistem dan font Pdf standar segera sebelum dokumen Pdf apa pun dibuka. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Membuka font dengan jalur file font yang ditentukan. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Membuka font dengan aliran font yang ditentukan. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Membuka font dengan jalur file font dan jalur file metrik yang ditentukan. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Memuat ulang semua font yang ditentukan oleh properti [`Sources`](./sources/) |

## Contoh

Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama.

```csharp
// Temukan font
Font font = FontRepository.FindFont("Arial");

// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


