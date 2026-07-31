---
title: "Kelas HtmlFragment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.HtmlFragment. Mewakili fragmen html"
type: docs
weight: 5650
url: /id/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

Mewakili HtmlFragment.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Menginisialisasi instance baru dari kelas HtmlFragment. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Mendapatkan atau mengatur HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ketika diperlukan pengaturan khusus untuk mengimpor HTML untuk instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk HTML yang diimpor atau harus menggunakan pemuat sumber daya eksternal khusus). Jika parameter adalah default (null), maka opsi pemuatan HTML standar akan digunakan. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Mendapatkan atau mengatur pemecahan kata. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Mendapatkan atau mengatur font |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Mengkloning fragmen html. |

### Lihat Juga

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


