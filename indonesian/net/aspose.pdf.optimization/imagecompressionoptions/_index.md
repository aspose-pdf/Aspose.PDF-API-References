---
title: "Kelas ImageCompressionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions kelas. Kelas yang berisi sekumpulan opsi untuk kompresi gambar."
type: docs
weight: 8090
url: /id/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

Kelas berisi sekumpulan opsi untuk kompresi gambar.

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
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Mendapatkan atau mengatur encoding yang digunakan untuk menyimpan gambar. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Jika bendera ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar daripada parameter MaxResolution yang ditentukan. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. fast (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. mixed (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\". |

### Lihat Juga

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


