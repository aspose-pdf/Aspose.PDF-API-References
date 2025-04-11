---
title: PdfPageEditor.GetPages
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 方法。返回总页数
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages 方法

返回总页数。

```csharp
public int GetPages()
```

### 返回值

页数。

## 示例

以下示例演示了如何使用 GetPages() 方法：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 另请参阅

* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)