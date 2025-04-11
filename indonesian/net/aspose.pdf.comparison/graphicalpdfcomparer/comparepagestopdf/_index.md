---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: Metode GraphicalPdfComparer. Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF
type: docs
weight: 80
url: /id/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page1 | Page | Halaman pertama. |
| page2 | Page | Halaman kedua. |
| resultPdfPath | String | Jalur ke file pdf target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Jika halaman yang dibandingkan memiliki ukuran yang berbeda. Jika resultPdfPath adalah null atau string kosong. |

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page1 | Page | Halaman pertama. |
| page2 | Page | Halaman kedua. |
| pdfDocument | Document | Instansi dokumen pdf. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Jika halaman yang dibandingkan memiliki ukuran yang berbeda. |

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)