---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.HtmlFragment. Mewakili fragmen html
type: docs
weight: 5520
url: /id/net/aspose.pdf/htmlfragment/
---
## Kelas HtmlFragment

Mewakili fragmen html.

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
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Mendapatkan atau mengatur HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ini ketika perlu menggunakan pengaturan spesifik untuk impor HTML untuk instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath spesifik untuk HTML yang diimpor atau harus menggunakan pemuat spesifik untuk sumber daya eksternal) Jika parameter adalah default (null), maka opsi pemuatan HTML standar akan digunakan. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Mendapatkan atau mengatur pemutusan kata |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf sebagai inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Mendapatkan atau mengatur font |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex bisa negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Mengkloning fragmen html. |

### Lihat Juga

* kelas [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)