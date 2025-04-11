---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Comparison.ImagesDifference. Mewakili kelas hasil dari membandingkan dua halaman PDF
type: docs
weight: 3230
url: /id/net/aspose.pdf.comparison/imagesdifference/
---
## Kelas ImagesDifference

Mewakili kelas hasil dari membandingkan dua halaman PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Mendapatkan array perbedaan. Array ini mirip dengan array data gambar asli yang diperoleh sebagai hasil dari metode LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Tinggi perbedaan. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Mendapatkan gambar dari halaman pertama yang dibandingkan. Gambar memiliki format piksel 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Langkah data gambar perbedaan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Mengonversi array perbedaan menjadi gambar bitmap menggunakan warna yang ditentukan. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Melakukan operasi pembersihan yang diperlukan sebelum objek dihancurkan. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Mengembalikan bitmap baru yang mewakili gambar tujuan dengan menerapkan array perbedaan ke gambar sumber. |

### Lihat Juga

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)