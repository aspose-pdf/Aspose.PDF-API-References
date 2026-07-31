---
title: "Kelas TextFragmentAbsorber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextFragmentAbsorber. Mewakili objek penyerap fragmen teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi TextFragments."
type: docs
weight: 11130
url: /id/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Mewakili objek penyerap fragmen teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Menginisialisasi instance baru dari `TextFragmentAbsorber` yang melakukan pencarian semua segmen teks dalam dokumen atau halaman. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk objek kelas System.Text.RegularExpressions.Regex yang ditentukan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Menginisialisasi instance baru dari `TextFragmentAbsorber` dengan opsi penyuntingan teks, yang melakukan pencarian semua segmen teks dalam dokumen atau halaman. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi penyuntingan teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi penyuntingan teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan dan opsi pencarian teks. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Menginisialisasi instance baru dari kelas `TextFragmentAbsorber` untuk frasa teks yang ditentukan, opsi pencarian teks, dan opsi penyuntingan teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Daftar objek [`TextExtractionError`](../textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Mendapatkan atau mengatur opsi ekstraksi teks. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal itu dapat menurunkan kinerja. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Mendapatkan atau mengatur frasa yang dicari oleh `TextFragmentAbsorber` pada dokumen PDF atau halaman. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Mendapatkan kamus kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan [`TextFragment`](../textfragment/) sebagai nilai. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Mendapatkan teks yang diekstrak yang diambil oleh [`TextAbsorber`](../textabsorber/) pada dokumen PDF atau halaman. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Mendapatkan atau mengatur opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Menerapkan ukuran font untuk semua fragmen teks yang diserap. Ini bekerja lebih cepat daripada mengulang melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, ia bekerja serupa dengan pengulangan. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Menerapkan font untuk semua fragmen teks yang diserap. Ini bekerja lebih cepat daripada mengulang melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, ia bekerja serupa dengan pengulangan. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Menerapkan font dan ukuran untuk semua fragmen teks yang diserap. Ini bekerja lebih cepat daripada mengulang melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, ia bekerja serupa dengan pengulangan. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Menghapus semua teks dari dokumen. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Menghapus semua teks dari halaman yang ditentukan. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Menghapus teks di dalam Rectangle yang ditentukan dari halaman yang ditentukan. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Menghapus koleksi TextFragments dari objek `TextFragmentAbsorber` ini. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Melakukan pencarian pada dokumen yang ditentukan. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Melakukan pencarian pada halaman yang ditentukan. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Melakukan pencarian pada objek form yang ditentukan. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Mengekstrak teks pada XForm yang ditentukan. |

## Catatan

Objek `TextFragmentAbsorber` pada dasarnya digunakan dalam skenario pencarian teks. Ketika pencarian selesai, kejadian-kejadian tersebut direpresentasikan dengan objek [`TextFragment`](../textfragment/) yang terdapat dalam koleksi [`TextFragments`](./textfragments/). Objek [`TextFragment`](../textfragment/) menyediakan akses ke teks kejadian pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

## Contoh

Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah teks dan font pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


