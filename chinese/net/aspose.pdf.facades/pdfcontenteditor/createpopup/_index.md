---
title: CreatePopup
second_title: Aspose.PDF for .NET API 参考
description: 在 PDF 文档中创建弹出注释
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

在 PDF 文档中创建弹出注释。

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 定义页面上注释位置的注释矩形。 |
| contents | String | 注释的内容。 |
| open | Boolean | 一个标志，指定弹出注释是否最初应打开显示。 |
| page | Int32 | 将在其中创建注释的原始页数。 |

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->