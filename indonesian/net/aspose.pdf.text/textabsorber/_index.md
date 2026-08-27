---
title: "Kelas TextAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextAbsorber. Mewakili objek penyerap teks. Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek Text."
type: docs
weight: 10980
url: /id/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Mewakili objek penyerap teks. Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Menginisialisasi instance baru dari `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Menginisialisasi instance baru dari `TextAbsorber` dengan opsi ekstraksi. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Menginisialisasi instance baru dari `TextAbsorber` dengan opsi pencarian teks. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Menginisialisasi instance baru dari `TextAbsorber` dengan opsi ekstraksi dan pencarian teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Daftar objek [`TextExtractionError`](../textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Mendapatkan atau mengatur opsi ekstraksi teks. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal itu dapat menurunkan kinerja. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Mendapatkan teks yang diekstrak yang diambil oleh `TextAbsorber` pada dokumen PDF atau halaman. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Mengekstrak teks pada dokumen yang ditentukan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Mengekstrak teks pada halaman yang ditentukan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Mengekstrak teks pada XForm yang ditentukan. |

## Catatan

Objek `TextAbsorber` digunakan untuk mengekstrak teks dari dokumen Pdf atau halaman dokumen tersebut.

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// buka dokumen
Document doc = new Document(inFile);

// buat objek TextAbsorber untuk mengekstrak teks
TextAbsorber absorber = new TextAbsorber();

// terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// dapatkan teks yang diekstrak
string extractedText = absorber.Text;

```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


