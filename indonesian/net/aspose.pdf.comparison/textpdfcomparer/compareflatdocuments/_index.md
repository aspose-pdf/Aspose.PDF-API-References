---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: Metode TextPdfComparer. Membandingkan dua dokumen halaman demi halaman. Dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks dari halaman dokumen digabungkan menjadi satu teks
type: docs
weight: 50
url: /id/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Membandingkan dua dokumen halaman demi halaman. Dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks dari halaman dokumen digabungkan menjadi satu teks.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama. |
| document2 | Document | Dokumen kedua. |
| options | ComparisonOptions | Opsi perbandingan. |

### Return Value

Daftar perubahan.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Membandingkan dua dokumen halaman demi halaman. Hasilnya disimpan dalam file PDF. Dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks dari halaman dokumen digabungkan menjadi satu teks.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama. |
| document2 | Document | Dokumen kedua. |
| options | ComparisonOptions | Opsi perbandingan. |
| resultPdfDocumentPath | String | Jalur ke file pdf untuk menyimpan hasil perbandingan. |

### Return Value

Daftar perubahan.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)