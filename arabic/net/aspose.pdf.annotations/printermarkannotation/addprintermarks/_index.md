---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PrinterMarkAnnotation. تضيف علامات الطابعة إلى جميع الصفحات في المستند المحدد
type: docs
weight: 10
url: /ar/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

تضيف علامات الطابعة إلى جميع الصفحات في المستند المحدد.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند الذي ستضاف إليه علامات الطابعة. |
| marksKind | PrinterMarksKind | نوع علامات الطابعة التي ستضاف. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | يتم طرحه عندما يكون *document* فارغًا. |

## Remarks

تضيف هذه الطريقة أنواعًا مختلفة من علامات الطابعة بناءً على العلامات المقدمة [`PrinterMarksKind`](../../printermarkskind/). إذا تم تقديم None، فلن تتم إضافة أي علامات.

### See Also

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

تضيف علامات الطابعة إلى الصفحة المحددة.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | الصفحة التي ستضاف إليها علامات الطابعة. |
| marksKind | PrinterMarksKind | نوع علامات الطابعة التي ستضاف. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | يتم طرحه عندما تكون *page* فارغة. |

## Remarks

تضيف هذه الطريقة أنواعًا مختلفة من علامات الطابعة بناءً على العلامات المقدمة [`PrinterMarksKind`](../../printermarkskind/). إذا تم تقديم None، فلن تتم إضافة أي علامات.

### See Also

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)