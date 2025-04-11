---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。用另一个图像替换 PDF 文档指定页面上的指定图像
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage 方法

用另一个图像替换 PDF 文档指定页面上的指定图像。

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 替换图像的页面编号。 |
| index | Int32 | 必须替换的图像对象的索引。 |
| imageFile | String | 将用于替换的图像文件。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)