---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Metode PrinterMarkAnnotation. Menambahkan tanda printer ke semua halaman dalam dokumen yang ditentukan
type: docs
weight: 10
url: /id/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Menambahkan tanda printer ke semua halaman dalam dokumen yang ditentukan.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen yang akan ditambahkan tanda printer. |
| marksKind | PrinterMarksKind | Jenis tanda printer yang akan ditambahkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* adalah null. |

## Catatan

Metode ini menambahkan berbagai jenis tanda printer berdasarkan bendera [`PrinterMarksKind`](../../printermarkskind/) yang diberikan. Jika None diberikan, tidak ada tanda yang ditambahkan.

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* kelas [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Menambahkan tanda printer ke halaman yang ditentukan.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Page | Halaman yang akan ditambahkan tanda printer. |
| marksKind | PrinterMarksKind | Jenis tanda printer yang akan ditambahkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *page* adalah null. |

## Catatan

Metode ini menambahkan berbagai jenis tanda printer berdasarkan bendera [`PrinterMarksKind`](../../printermarkskind/) yang diberikan. Jika None diberikan, tidak ada tanda yang ditambahkan.

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* kelas [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)