---
title: ReplaceImage
second_title: Aspose.PDF for .NET API 参考
description: 将 PDF 文档指定页面上的指定图像替换为另一个图像
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

将 PDF 文档指定页面上的指定图像替换为另一个图像。

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 替换图像的页数。 |
| index | Int32 | 必须替换图像对象的索引。 |
| imageFile | String | 图像文件将用于替换。 |

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
