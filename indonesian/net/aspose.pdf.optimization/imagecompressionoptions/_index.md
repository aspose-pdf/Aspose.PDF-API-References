---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Optimization.ImageCompressionOptions. Kelas ini berisi opsi untuk kompresi gambar
type: docs
weight: 7950
url: /id/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Kelas OpsiKompresiGambar

Kelas ini berisi opsi untuk kompresi gambar.

```csharp
public class ImageCompressionOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. tingkat kompresi ditentukan dengan properti ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Mendapatkan atau mengatur encoding yang digunakan untuk menyimpan gambar. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, itu akan diskalakan. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Jika flag ini diatur ke true dan CompressImages adalah true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat dari standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini mungkin memberikan kompresi terbaik tetapi lebih lambat dari algoritma "cepat". Versi "Cepat" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah "Standar". |

### Lihat Juga

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)