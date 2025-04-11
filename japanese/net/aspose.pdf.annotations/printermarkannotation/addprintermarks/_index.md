---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: PrinterMarkAnnotation メソッド。指定されたドキュメントのすべてのページにプリンターマークを追加します
type: docs
weight: 10
url: /ja/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

指定されたドキュメントのすべてのページにプリンターマークを追加します。

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | Document | プリンターマークが追加されるドキュメント。 |
| marksKind | PrinterMarksKind | 追加するプリンターマークの種類。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null の場合にスローされます。 |

## 備考

このメソッドは、提供された [`PrinterMarksKind`](../../printermarkskind/) フラグに基づいてさまざまな種類のプリンターマークを追加します。None が提供された場合、マークは追加されません。

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* 列挙型 [PrinterMarksKind](../../printermarkskind/)
* クラス [PrinterMarkAnnotation](../)
* 名前空間 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

指定されたページにプリンターマークを追加します。

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Page | プリンターマークが追加されるページ。 |
| marksKind | PrinterMarksKind | 追加するプリンターマークの種類。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *page* が null の場合にスローされます。 |

## 備考

このメソッドは、提供された [`PrinterMarksKind`](../../printermarkskind/) フラグに基づいてさまざまな種類のプリンターマークを追加します。None が提供された場合、マークは追加されません。

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* 列挙型 [PrinterMarksKind](../../printermarkskind/)
* クラス [PrinterMarkAnnotation](../)
* 名前空間 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../../)