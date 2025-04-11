---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation 方法。将打印机标记添加到指定文档的所有页面
type: docs
weight: 10
url: /zh/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

将打印机标记添加到指定文档的所有页面。

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要添加打印机标记的文档。 |
| marksKind | PrinterMarksKind | 要添加的打印机标记的类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |

## 备注

此方法根据提供的 [`PrinterMarksKind`](../../printermarkskind/) 标志添加各种类型的打印机标记。如果提供 None，则不添加任何标记。

### 另请参阅

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

将打印机标记添加到指定页面。

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Page | 要添加打印机标记的页面。 |
| marksKind | PrinterMarksKind | 要添加的打印机标记的类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *page* 为 null 时抛出。 |

## 备注

此方法根据提供的 [`PrinterMarksKind`](../../printermarkskind/) 标志添加各种类型的打印机标记。如果提供 None，则不添加任何标记。

### 另请参阅

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)