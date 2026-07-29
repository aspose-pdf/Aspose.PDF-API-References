---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PrinterMarkAnnotation. تضيف علامات الطابعة إلى جميع الصفحات في المستند المحدد"
type: docs
weight: 10
url: /ar/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

يضيف علامات الطابعة إلى جميع الصفحات في المستند المحدد.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند الذي ستُضاف إليه علامات الطابعة. |
| marksKind | PrinterMarksKind | نوع علامات الطابعة التي سيتم إضافتها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *document* فارغًا. |

## ملاحظات

هذه الطريقة تضيف أنواعًا مختلفة من علامات الطابعة بناءً على العلامات [`PrinterMarksKind`](../../printermarkskind/) المقدمة. إذا تم تقديم None، لن تُضاف أي علامات.

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

يضيف علامات الطابعة إلى الصفحة المحددة.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | الصفحة التي ستُضاف إليها علامات الطابعة. |
| marksKind | PrinterMarksKind | نوع علامات الطابعة التي سيتم إضافتها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *page* فارغًا. |

## ملاحظات

هذه الطريقة تضيف أنواعًا مختلفة من علامات الطابعة بناءً على العلامات [`PrinterMarksKind`](../../printermarkskind/) المقدمة. إذا تم تقديم None، لن تُضاف أي علامات.

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


