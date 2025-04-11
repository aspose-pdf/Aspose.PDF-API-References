---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Comparison.GraphicalPdfComparer. Mewakili kelas untuk membandingkan dokumen PDF secara grafis. Harus digunakan untuk mencari perubahan kecil yang terutama bersifat grafis. Untuk membandingkan perubahan konten teks, gunakan kelas perbandingan PDF lainnya.
type: docs
weight: 3190
url: /id/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Kelas GraphicalPdfComparer

Mewakili kelas untuk membandingkan dokumen PDF secara grafis. Harus digunakan untuk mencari perubahan kecil, terutama yang bersifat grafis. Untuk membandingkan perubahan konten teks, gunakan kelas perbandingan PDF lainnya.

```csharp
public class GraphicalPdfComparer
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Mendapatkan dan mengatur warna bendera perubahan. Warna default adalah merah. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Mendapatkan dan mengatur resolusi gambar yang dihasilkan. Nilai default adalah 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Mendapatkan dan mengatur nilai ambang dalam persentase. Nilai ini memungkinkan Anda untuk mengabaikan perubahan kecil jika tidak signifikan bagi Anda. Nilai default adalah 0%. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam gambar. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam sebuah gambar. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Mendapatkan perbedaan antara gambar halaman. Hasilnya berisi gambar halaman pertama yang dibandingkan dan array perbedaan. |

### Lihat Juga

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)