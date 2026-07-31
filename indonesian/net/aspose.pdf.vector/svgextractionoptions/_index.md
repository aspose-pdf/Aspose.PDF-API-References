---
title: "Kelas SvgExtractionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Vector.SvgExtractionOptions. Mewakili kelas opsi untuk mengekstrak grafik vektor dari halaman dokumen pdf"
type: docs
weight: 11430
url: /id/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Mewakili kelas opsi untuk mengekstrak grafik vektor dari halaman dokumen pdf.

```csharp
public class SvgExtractionOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Mendapatkan dan mengatur opsi untuk secara otomatis mengelompokkan subpath menjadi gambar. Opsi ini mengecualikan opsi [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF menjadi gambar SVG terpisah. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Mendapatkan dan mengatur persegi panjang pembatas yang mendefinisikan area ekstraksi untuk ekstraksi SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Mendapatkan dan mengatur opsi Kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda mengkonfigurasi tingkat pengelompokan subpath. Nilai berkisar dari 0 hingga 1. Nilai 0 berarti opsi [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) diaktifkan. Nilai 1 akan membuat satu gambar tunggal untuk semua jalur vektor pada halaman. Opsi ini berpengaruh ketika [`AutoGrouping`](./autogrouping/) bernilai false. Nilai default adalah `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Mendapatkan atau mengatur lebar goresan minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar goresan yang lebih tipis, itu akan diganti dengan lebar ini. Nilai default adalah 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di [`ExtractionAreaBound`](./extractionareabound/). Jika disetel ke false, maka subpath yang tidak sepenuhnya termasuk dalam [`ExtractionAreaBound`](./extractionareabound/) akan diekstrak. Nilai default adalah `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Mendapatkan dan mengatur flag yang menentukan apakah XFrom yang ditemukan pada halaman harus dibongkar atau tidak. Elemen XFrom dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang dibongkar. XForms bersarang tidak dibongkar. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Mendapatkan dan mengatur opsi untuk membongkar hanya XForm yang sesuai dengan predikat yang ditentukan. |

### Lihat Juga

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


