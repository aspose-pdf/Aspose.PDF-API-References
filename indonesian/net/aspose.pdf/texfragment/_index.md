---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.TeXFragment. Mewakili fragmen TeX
type: docs
weight: 10360
url: /id/net/aspose.pdf/texfragment/
---
## Kelas TeXFragment

Mewakili fragmen TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Menginisialisasi instance baru dari kelas HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Menginisialisasi instance baru dari kelas HtmlFragment. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur penyelarasan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Mendapatkan atau mengatur TeXLoadOptions yang akan digunakan untuk memuat (dan merender) LaTeX ke dalam instance kelas ini. Harap gunakan ini ketika perlu menggunakan pengaturan spesifik untuk impor LaTeX untuk instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath spesifik untuk LaTeX yang diimpor atau harus menggunakan pemuat spesifik untuk sumber daya eksternal) Jika parameter adalah default (null), maka opsi pemuatan LaTeX standar akan digunakan. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur penyelarasan vertikal paragraf |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Mengkloning fragmen. |

### Lihat Juga

* kelas [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)