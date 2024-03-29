---
title: CreateFreeText
second_title: Aspose.PDF for .NET API 参考
description: 在 PDF 文档中创建自由文本注释
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

在 PDF 文档中创建自由文本注释

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 定义页面上注释位置的注释矩形。 |
| contents | String | 注释的内容。 |
| page | Int32 | 将在其中创建文本注释的原始页数。 |

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
