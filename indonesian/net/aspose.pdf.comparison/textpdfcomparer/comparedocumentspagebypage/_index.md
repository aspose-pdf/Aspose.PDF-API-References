---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Metode TextPdfComparer. Membandingkan dua dokumen halaman demi halaman
type: docs
weight: 40
url: /id/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Membandingkan dua dokumen halaman demi halaman.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama.. |
| document2 | Document | Dokumen kedua. |
| options | ComparisonOptions | Opsi perbandingan. |

### Nilai Kembali

Daftar perubahan per halaman.

### Lihat Juga

* kelas [DiffOperation](../../diffoperation/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [ComparisonOptions](../../comparisonoptions/)
* kelas [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Membandingkan dua dokumen halaman demi halaman. Hasilnya disimpan dalam file PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama.. |
| document2 | Document | Dokumen kedua. |
| options | ComparisonOptions | Opsi perbandingan. |
| resultPdfDocumentPath | String | Jalur ke file pdf untuk menyimpan hasil perbandingan. |

### Nilai Kembali

Daftar perubahan per halaman.

### Lihat Juga

* kelas [DiffOperation](../../diffoperation/)
* kelas [Document](../../../aspose.pdf/document/)
* kelas [ComparisonOptions](../../comparisonoptions/)
* kelas [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)