---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextFragment. Mewakili fragmen teks Pdf
type: docs
weight: 10940
url: /id/net/aspose.pdf.text/textfragment/
---
## Kelas TextFragment

Mewakili fragmen teks Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Menginisialisasi instance baru dari objek `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Membuat objek `TextFragment` dengan satu objek [`TextSegment`](../textsegment/) di dalamnya. Menentukan string teks di dalam segmen. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Menginisialisasi instance baru dari objek `TextFragment` dengan posisi [`TabStops`](../tabstops/) yang telah ditentukan. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Membuat objek `TextFragment` dengan satu objek [`TextSegment`](../textsegment/) di dalamnya dan posisi [`TabStops`](../tabstops/) yang telah ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang diwakili dengan objek `TextFragment`. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Mendapatkan atau menetapkan catatan akhir paragraf. (hanya untuk generasi pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Mendapatkan atau menetapkan catatan kaki paragraf. (hanya untuk generasi pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Mendapatkan objek form yang berisi TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan horizontal dari fragmen teks. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Menetapkan hyperlink fragmen |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau menetapkan apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau menetapkan margin luar untuk paragraf (untuk generasi pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Mendapatkan halaman yang berisi TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Mendapatkan atau menetapkan posisi teks untuk teks, yang diwakili dengan objek `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Mendapatkan opsi penggantian teks. Opsi ini mendefinisikan perilaku ketika teks fragmen diganti dengan yang lebih pendek/panjang. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mendapatkan segmen teks untuk `TextFragment` saat ini. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Mendapatkan atau menetapkan objek teks String yang diwakili oleh objek `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Mendapatkan atau menetapkan opsi edit teks. Opsi ini mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Mendapatkan atau menetapkan status teks untuk teks yang diwakili oleh objek `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan vertikal dari fragmen teks. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Mendapatkan atau menetapkan jumlah baris pembungkus untuk paragraf ini (hanya untuk generasi pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau menetapkan nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Mengkloning fragmen. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Mengkloning fragmen dengan semua segmen. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Mendapatkan [`TextSegment`](../textsegment/)(s) yang mewakili bagian tertentu dari teks `TextFragment`. |

## Catatan

Dalam beberapa kata, objek `TextFragment` berisi daftar objek [`TextSegment`](../textsegment/). Secara rinci: Teks dokumen pdf dalam Pdf diwakili oleh dua objek dasar: `TextFragment` dan [`TextSegment`](../textsegment/). Perbedaan antara keduanya sebagian besar tergantung pada konteks. Mari kita pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk beroperasi dengannya, mengubah propertinya, melihat, dll.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Representasi teks pdf secara fisik sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek `TextFragment` menyediakan satu set operasi logis di atas sekumpulan objek fisik [`TextSegment`](../textsegment/) yang mewakili kueri pengguna. Dalam skenario pencarian teks, `TextFragment` adalah representasi logis dari teks "hello world", dan koleksi objek [`TextSegment`](../textsegment/) mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, `TextFragment` mendekati representasi teks logis. Dan [`TextSegment`](../textsegment/) mendekati representasi teks fisik. Jelas bahwa setiap objek [`TextSegment`](../textsegment/) dapat memiliki font, pewarnaan, dan properti penempatan sendiri. `TextFragment` menyediakan cara sederhana untuk mengubah teks dengan propertinya: menetapkan font, menetapkan ukuran font, menetapkan warna font, dll. Sementara itu, objek [`TextSegment`](../textsegment/) dapat diakses dan pengguna dapat beroperasi dengan objek [`TextSegment`](../textsegment/) secara independen. Perhatikan bahwa mengubah properti TextFragment dapat mengubah koleksi [`Segments`](./segments/) internal karena TextFragment adalah objek agregat dan dapat mengatur ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah untuk membiarkan koleksi [`Segments`](./segments/) tidak berubah, silakan ubah segmen internal secara individu.

## Contoh

Contoh ini menunjukkan bagaimana menemukan teks di halaman pertama dokumen PDF dan mengganti teks serta font-nya.

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

* kelas [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)