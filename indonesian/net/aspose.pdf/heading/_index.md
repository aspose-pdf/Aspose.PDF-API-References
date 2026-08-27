---
title: "Kelas Heading"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Heading. Mewakili heading"
type: docs
weight: 5590
url: /id/net/aspose.pdf/heading/
---
## Heading class

Mewakili judul.

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
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek [`TextFragment`](../../aspose.pdf.text/textfragment/). YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Mendapatkan halaman tujuan. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Mendapatkan atau mengatur catatan akhir paragraf. (hanya untuk pembuatan pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Mendapatkan atau mengatur catatan kaki paragraf. (hanya untuk pembuatan pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Mendapatkan objek form yang berisi TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal fragmen teks. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Mengatur hyperlink fragmen |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Mendapatkan apakah heading harus diberi nomor secara otomatis. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Mendapatkan apakah heading harus berada dalam daftar toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Mendapatkan level. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Mendapatkan halaman yang berisi TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Mendapatkan atau mengatur posisi teks untuk teks, yang direpresentasikan dengan objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mendapatkan segmen teks untuk [`TextFragment`](../../aspose.pdf.text/textfragment/) saat ini. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Mendapatkan nomor awal heading. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Mendapatkan atau mengatur gaya. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Mendapatkan atau mengatur objek teks String yang direpresentasikan oleh objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Mendapatkan atau mengatur status teks untuk teks yang direpresentasikan oleh objek [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Mendapatkan halaman yang berisi heading ini. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Mendapatkan Y atas dari heading ini. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Mendapatkan atau mengatur label pengguna. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal fragmen teks. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Mendapatkan atau mengatur jumlah baris pembungkus untuk paragraf ini (hanya untuk pembuatan pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Menggandakan heading. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Menggandakan heading dengan semua segmen. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Mendapatkan [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) yang merepresentasikan bagian tertentu dari teks [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Lihat Juga

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


