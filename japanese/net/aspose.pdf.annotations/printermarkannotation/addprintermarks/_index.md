---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PrinterMarkAnnotation メソッド。指定された Document のすべてのページにプリンターマークを追加します"
type: docs
weight: 10
url: /ja/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

指定されたドキュメントのすべてのページにプリンターのマークを追加します。

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Document | プリンターのマークが追加されるドキュメント。 |
| marksKind | PrinterMarksKind | 追加するプリンターのマークの種類。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |

## 備考

このメソッドは、提供された [`PrinterMarksKind`](../../printermarkskind/) フラグに基づいてさまざまなタイプのプリンターのマークを追加します。None が指定された場合、マークは追加されません。

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

指定されたページにプリンターのマークを追加します。

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | プリンターのマークが追加されるページ。 |
| marksKind | PrinterMarksKind | 追加するプリンターのマークの種類。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *page* が null のときにスローされます。 |

## 備考

このメソッドは、提供された [`PrinterMarksKind`](../../printermarkskind/) フラグに基づいてさまざまなタイプのプリンターのマークを追加します。None が指定された場合、マークは追加されません。

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


