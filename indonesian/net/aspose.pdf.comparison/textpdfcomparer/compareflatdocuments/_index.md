---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextPdfComparer. Membandingkan dua dokumen halaman per halaman. Dokumen-dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks dari halaman dokumen digabung menjadi satu teks."
type: docs
weight: 50
url: /id/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Membandingkan dua dokumen halaman per halaman. Dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks halaman dokumen digabung menjadi satu teks.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama. |
| document2 | Document | Dokumen kedua. |
| options | ComparisonOptions | Opsi perbandingan. |

### Nilai Kembalian

Daftar perubahan.

### Lihat Juga

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Membandingkan dua dokumen halaman per halaman. Hasil disimpan dalam file PDF. Dokumen dibandingkan secara keseluruhan. Sebelum membandingkan teks, teks halaman dokumen digabung menjadi satu teks.

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

### Nilai Kembalian

Daftar perubahan.

### Lihat Juga

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


