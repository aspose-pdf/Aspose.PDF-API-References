---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation metodu. Belirtilen belgedeki tüm sayfalara yazıcı işaretleri ekler
type: docs
weight: 10
url: /tr/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Belirtilen belgedeki tüm sayfalara yazıcı işaretleri ekler.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | Document | Yazıcı işaretlerinin ekleneceği belge. |
| marksKind | PrinterMarksKind | Eklenecek yazıcı işaretlerinin türü. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentNullException | *document* null olduğunda fırlatılır. |

## Açıklamalar

Bu yöntem, sağlanan [`PrinterMarksKind`](../../printermarkskind/) bayraklarına dayalı olarak çeşitli türde yazıcı işaretleri ekler. Hiçbiri sağlanmazsa, işaret eklenmez.

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* sınıf [PrinterMarkAnnotation](../)
* ad alanı [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Belirtilen sayfaya yazıcı işaretleri ekler.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | Yazıcı işaretlerinin ekleneceği sayfa. |
| marksKind | PrinterMarksKind | Eklenecek yazıcı işaretlerinin türü. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentNullException | *page* null olduğunda fırlatılır. |

## Açıklamalar

Bu yöntem, sağlanan [`PrinterMarksKind`](../../printermarkskind/) bayraklarına dayalı olarak çeşitli türde yazıcı işaretleri ekler. Hiçbiri sağlanmazsa, işaret eklenmez.

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* sınıf [PrinterMarkAnnotation](../)
* ad alanı [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../../)