---
title: "SideBySidePdfComparer.Compare"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode SideBySidePdfComparer. Membandingkan dua halaman. Hasilnya disimpan dalam dokumen PDF di mana halaman pertama ditulis terlebih dahulu kemudian halaman kedua. Anda dapat membukanya di Adobe Acrobat dalam tampilan dua halaman untuk melihat perubahan berdampingan. Penghapusan dicatat pada halaman kiri dan penyisipan dicatat pada halaman kanan."
type: docs
weight: 10
url: /id/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Membandingkan dua halaman. Hasil disimpan dalam dokumen PDF di mana halaman pertama ditulis terlebih dahulu, kemudian halaman kedua. Anda dapat membukanya di Adobe Acrobat dalam tampilan dua halaman untuk melihat perubahan berdampingan. Penghapusan ditandai pada halaman sebelah kiri, dan penyisipan ditandai pada halaman sebelah kanan.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page1 | Halaman | Halaman pertama untuk dibandingkan. |
| page2 | Halaman | Halaman pertama untuk dibandingkan. |
| targetPdfPath | String | Jalur ke file PDF untuk menyimpan hasil perbandingan. |
| options | SideBySideComparisonOptions | Opsi perbandingan. |

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Membandingkan dua dokumen. Halaman dibandingkan satu per satu. Halaman dokumen yang dibandingkan disalin satu demi satu ke dalam dokumen hasil. Pertama halaman pertama dari dokumen pertama, kemudian halaman pertama dari dokumen kedua. Selanjutnya halaman kedua dari dokumen pertama dan kemudian halaman kedua dari dokumen kedua, dan seterusnya. Anda dapat membukanya di Adobe Acrobat dalam tampilan dua halaman untuk melihat perubahan berdampingan. Penghapusan ditandai pada halaman sebelah kiri, dan penyisipan ditandai pada halaman sebelah kanan.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document1 | Document | Dokumen pertama untuk dibandingkan. |
| document2 | Document | Dokumen kedua untuk dibandingkan. |
| targetPdfPath | String | Jalur ke file PDF untuk menyimpan hasil perbandingan. |
| options | SideBySideComparisonOptions | Opsi perbandingan. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


