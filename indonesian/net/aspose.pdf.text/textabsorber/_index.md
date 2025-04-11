---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextAbsorber. Mewakili objek penyerap teks. Melakukan ekstraksi teks dan memberikan akses ke hasil melalui objek [`Text`](./text/)
type: docs
weight: 10800
url: /id/net/aspose.pdf.text/textabsorber/
---
## Kelas TextAbsorber

Mewakili objek penyerap teks. Melakukan ekstraksi teks dan memberikan akses ke hasil melalui objek [`Text`](./text/).

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
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Daftar objek [`TextExtractionError`](../textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan ini dapat mengurangi kinerja. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Mendapatkan atau mengatur opsi ekstraksi teks. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Nilai yang menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan ini dapat mengurangi kinerja. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Mendapatkan teks yang diekstrak yang diekstrak oleh `TextAbsorber` pada dokumen atau halaman PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Mengekstrak teks pada dokumen yang ditentukan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Mengekstrak teks pada halaman yang ditentukan |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Mengekstrak teks pada XForm yang ditentukan. |

## Catatan

Objek `TextAbsorber` digunakan untuk mengekstrak teks dari dokumen Pdf atau halaman dokumen.

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)