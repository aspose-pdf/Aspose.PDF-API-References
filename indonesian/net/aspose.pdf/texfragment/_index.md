---
title: "Kelas TeXFragment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.TeXFragment. Mewakili fragmen TeX."
type: docs
weight: 10540
url: /id/net/aspose.pdf/texfragment/
---
## TeXFragment class

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Mendapatkan atau mengatur TeXLoadOptions yang akan digunakan untuk memuat (dan merender) LaTeX ke dalam instance kelas ini. Silakan gunakan ketika diperlukan pengaturan khusus untuk mengimpor LaTeX bagi instance tertentu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk LaTeX yang diimpor atau harus menggunakan pemuat khusus untuk sumber daya eksternal). Jika parameter bernilai default (null), maka opsi pemuatan LaTeX standar akan digunakan. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Mengkloning fragmen. |

### Lihat Juga

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


