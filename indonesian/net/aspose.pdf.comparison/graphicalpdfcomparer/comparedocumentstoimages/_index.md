---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode GraphicalPdfComparer. Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam gambar."
type: docs
weight: 50
url: /id/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam gambar.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama untuk dibandingkan. |
| document2 | Document | Dokumen kedua untuk dibandingkan. |
| targetDirectory | String | Direktori untuk menyimpan hasil perbandingan. |
| fileNamePrefix | String | Awalan nama gambar. |
| imageFormat | ImageFormat | Format gambar untuk disimpan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Jika halaman yang dibandingkan memiliki ukuran yang berbeda. Jika targetDirectory bernilai null atau string kosong. Jika fileNamePrefix bernilai null atau string kosong. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


