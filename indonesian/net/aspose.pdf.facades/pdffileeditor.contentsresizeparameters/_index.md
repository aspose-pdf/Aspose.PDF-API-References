---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan untuk mengatur parameter berikut Ukuran halaman hasil dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Margin Kiri, Atas, Bawah, dan Kanan dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Beberapa nilai dapat dibiarkan null untuk perhitungan otomatis. Nilai-nilai ini akan dihitung dari sisa ukuran halaman setelah perhitungan nilai yang ditentukan secara eksplisit. Kelas ini digunakan dalam metode ResizeContents.
type: docs
weight: 4480
url: /id/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## Kelas PdfFileEditor.ContentsResizeParameters

Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan untuk mengatur parameter berikut: Ukuran halaman hasil (lebar, tinggi) dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Margin Kiri, Atas, Bawah, dan Kanan dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Beberapa nilai dapat dibiarkan null untuk perhitungan otomatis. Nilai-nilai ini akan dihitung dari sisa ukuran halaman setelah perhitungan nilai yang ditentukan secara eksplisit. Misalnya: jika lebar halaman = 100 dan lebar halaman baru yang ditentukan 60 unit, maka margin kiri dan kanan dihitung secara otomatis: (100 - 60) / 2 = 15. Kelas ini digunakan dalam metode ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Membuat parameter pengubahan ukuran di mana semua nilai diatur ke "otomatis". Margin dan ukuran konten dapat ditentukan kemudian jika diperlukan. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Membuat parameter pengubahan ukuran dengan nilai margin dan ukuran konten yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Mendapatkan atau mengatur margin bawah pada halaman hasil. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Mendapatkan atau mengatur tinggi konten halaman sumber pada halaman hasil. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Mendapatkan atau mengatur lebar konten halaman sumber pada halaman hasil. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Mendapatkan atau mengatur margin kiri pada halaman hasil. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Mendapatkan atau mengatur margin kanan pada halaman hasil. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Mendapatkan atau mengatur margin atas pada halaman hasil. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan dalam persentase dari ukuran halaman awal. Margin dihitung secara otomatis. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Membuat parameter pengubahan ukuran dengan nilai margin yang ditentukan. Ukuran konten dihitung secara otomatis. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Membuat parameter pengubahan ukuran. Margin ditentukan dalam persentase dari ukuran halaman awal. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Membuat parameter pengubahan ukuran untuk pengubahan ukuran halaman. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Membuat parameter pengubahan ukuran untuk pengubahan ukuran halaman. Ukuran baru ditentukan dalam persentase. |

### Lihat Juga

* kelas [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)