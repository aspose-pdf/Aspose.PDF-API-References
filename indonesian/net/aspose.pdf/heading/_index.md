---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Heading. Mewakili heading
type: docs
weight: 5470
url: /id/net/aspose.pdf/heading/
---
## Kelas Heading

Mewakili heading.

```csharp
public sealed class Heading : TextFragment
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Heading](heading/)(int) | Menginisialisasi instance baru dari kelas Cell. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang diwakili dengan objek [`TextFragment`](../../aspose.pdf.text/textfragment/). YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Mendapatkan halaman tujuan. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Mendapatkan atau mengatur catatan akhir paragraf. (hanya untuk pembuatan pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Mendapatkan atau mengatur catatan kaki paragraf. (hanya untuk pembuatan pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Mendapatkan objek form yang berisi TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal dari fragmen teks. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Mengatur hyperlink fragmen |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Mendapatkan heading yang harus dinomori secara otomatis. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf sebagai inline. Default adalah false. (untuk pembuatan pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Mendapatkan heading yang harus ada dalam daftar toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk pembuatan pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Mendapatkan level. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Mendapatkan halaman yang berisi TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Mendapatkan atau mengatur posisi teks untuk teks, yang diwakili dengan objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Mendapatkan opsi penggantian teks. Opsi ini mendefinisikan perilaku ketika teks fragmen diganti dengan yang lebih pendek/panjang. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mendapatkan segmen teks untuk [`TextFragment`](../../aspose.pdf.text/textfragment/) saat ini. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Mendapatkan nomor awal heading. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Mendapatkan atau mengatur gaya. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Mendapatkan atau mengatur objek teks String yang diwakili oleh objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi edit teks. Opsi ini mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Mendapatkan atau mengatur status teks untuk teks yang diwakili oleh objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Mendapatkan halaman yang berisi heading ini. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Mendapatkan Y atas dari heading ini. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Mendapatkan atau mengatur label pengguna. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal dari fragmen teks. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Mendapatkan atau mengatur jumlah baris pembungkus untuk paragraf ini (hanya untuk pembuatan pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Mengkloning heading. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Mengkloning heading dengan semua segmen. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Mendapatkan [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) yang mewakili bagian tertentu dari teks [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Lihat Juga

* kelas [TextFragment](../../aspose.pdf.text/textfragment/)
* ruang nama [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)