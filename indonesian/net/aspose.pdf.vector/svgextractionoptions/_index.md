---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Vector.SvgExtractionOptions. Mewakili kelas opsi untuk mengekstrak grafik vektor dari halaman dokumen pdf
type: docs
weight: 11240
url: /id/net/aspose.pdf.vector/svgextractionoptions/
---
## Kelas SvgExtractionOptions

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
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF ke gambar SVG terpisah. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Mendapatkan dan mengatur persegi panjang batas yang mendefinisikan area ekstraksi untuk ekstraksi SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Mendapatkan dan mengatur opsi kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda untuk mengonfigurasi tingkat pengelompokan subpath. Rentang nilai adalah dari 0 hingga 1. Nilai 0 sesuai dengan opsi [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) yang diaktifkan. Nilai 1 akan membuat satu gambar untuk semua jalur vektor di halaman. Opsi ini berpengaruh ketika [`AutoGrouping`](./autogrouping/) adalah false. Nilai default adalah `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Mendapatkan atau mengatur lebar garis minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar garis yang lebih tipis, itu akan diganti dengan lebar ini. Nilai default adalah 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di [`ExtractionAreaBound`](./extractionareabound/). Jika diatur ke false, maka subpath yang tidak sepenuhnya termasuk dalam [`ExtractionAreaBound`](./extractionareabound/) akan diekstrak. Nilai default adalah `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Mendapatkan dan mengatur sebuah flag yang menentukan apakah XForm yang ditemukan di halaman harus diekstrak atau tidak. Elemen XForm dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang diekstrak. XForms bersarang tidak diekstrak. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Mendapatkan dan mengatur opsi untuk mengekstrak hanya XForm yang sesuai dengan predikat yang ditentukan. |

### Lihat Juga

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)