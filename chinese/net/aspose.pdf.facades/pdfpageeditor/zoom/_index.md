---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 属性。获取或设置缩放系数。值 1.0 对应于 100%。默认值为 1.0。以下示例演示如何更改文档页面的缩放。
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom 属性

获取或设置缩放系数。值 1.0 对应于 100%。默认值为 1.0。以下示例演示如何更改文档页面的缩放。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### 另请参阅

* 类 [PdfPageEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)