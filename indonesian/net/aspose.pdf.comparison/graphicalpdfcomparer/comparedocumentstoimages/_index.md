---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: Metode GraphicalPdfComparer. Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam gambar
type: docs
weight: 50
url: /id/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Metode GraphicalPdfComparer.CompareDocumentsToImages

Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam gambar.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama yang akan dibandingkan. |
| document2 | Document | Dokumen kedua yang akan dibandingkan. |
| targetDirectory | String | Direktori untuk menyimpan hasil perbandingan. |
| fileNamePrefix | String | Prefiks nama gambar. |
| imageFormat | ImageFormat | Format gambar untuk disimpan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Jika halaman yang dibandingkan memiliki ukuran yang berbeda. Jika targetDirectory adalah null atau string kosong. Jika fileNamePrefix adalah null atau string kosong. |

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)