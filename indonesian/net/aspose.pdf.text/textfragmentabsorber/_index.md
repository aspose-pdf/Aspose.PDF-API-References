---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextFragmentAbsorber. Mewakili objek penyerap fragmen teks. Melakukan pencarian teks dan memberikan akses ke hasil pencarian melalui koleksi TextFragments
type: docs
weight: 10950
url: /id/net/aspose.pdf.text/textfragmentabsorber/
---
## Kelas TextFragmentAbsorber

Mewakili objek penyerap fragmen teks. Melakukan pencarian teks dan memberikan akses ke hasil pencarian melalui koleksi [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Menginisialisasi instance baru dari `TextFragmentAbsorber` yang melakukan pencarian semua segmen teks dari dokumen atau halaman. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk objek kelas System.Text.RegularExpressions.Regex yang ditentukan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Menginisialisasi instance baru dari `TextFragmentAbsorber` dengan opsi edit teks, yang melakukan pencarian semua segmen teks dari dokumen atau halaman. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi edit teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi edit teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan, opsi pencarian teks dan opsi edit teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Daftar objek [`TextExtractionError`](../textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan ini dapat mengurangi kinerja. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Mendapatkan atau mengatur opsi ekstraksi teks. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Nilai yang menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan ini dapat mengurangi kinerja. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Mendapatkan atau mengatur frasa yang dicari oleh `TextFragmentAbsorber` pada dokumen atau halaman PDF. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Mendapatkan kamus dari kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan [`TextFragment`](../textfragment/) sebagai nilai. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Mendapatkan teks yang diekstrak yang diekstrak oleh [`TextAbsorber`](../textabsorber/) pada dokumen atau halaman PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi edit teks. Opsi ini mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Mendapatkan atau mengatur opsi penggantian teks. Opsi ini mendefinisikan perilaku ketika teks fragmen diganti dengan yang lebih pendek/panjang. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian. Opsi ini memungkinkan pencarian menggunakan ekspresi reguler. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Menerapkan ukuran font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan loop melalui fragmen jika semua fragmen di halaman telah diserap. Jika tidak, ini bekerja mirip dengan looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Menerapkan font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan loop melalui fragmen jika semua fragmen di halaman telah diserap. Jika tidak, ini bekerja mirip dengan looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Menerapkan font dan ukuran untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan loop melalui fragmen jika semua fragmen di halaman telah diserap. Jika tidak, ini bekerja mirip dengan looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Menghapus semua teks dari dokumen. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Menghapus semua teks dari halaman yang ditentukan. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Menghapus teks di dalam persegi panjang yang ditentukan dari halaman yang ditentukan. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Menghapus koleksi TextFragments dari objek `TextFragmentAbsorber` ini. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Melakukan pencarian pada dokumen yang ditentukan. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Melakukan pencarian pada halaman yang ditentukan. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Melakukan pencarian pada objek form yang ditentukan. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Mengekstrak teks pada XForm yang ditentukan. |

## Catatan

Objek `TextFragmentAbsorber` pada dasarnya digunakan dalam skenario pencarian teks. Ketika pencarian selesai, kejadian diwakili dengan objek [`TextFragment`](../textfragment/) yang dikandung oleh koleksi [`TextFragments`](./textfragments/). Objek [`TextFragment`](../textfragment/) memberikan akses ke teks kejadian pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah status teks (font, ukuran font, warna, dll).

## Contoh

Contoh ini menunjukkan bagaimana cara menemukan teks di halaman pertama dokumen PDF dan mengganti teks serta font-nya.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)