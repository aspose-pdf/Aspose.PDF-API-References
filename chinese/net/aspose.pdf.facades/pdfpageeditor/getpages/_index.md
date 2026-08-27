---
title: "PdfPageEditor.GetPages"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfPageEditor 方法。返回页面总数"
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages method

返回页面的总数。

```csharp
public int GetPages()
```

### 返回值

页面数量。

## 示例

以下示例演示了 GetPages() 方法的使用：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 另请参见

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


