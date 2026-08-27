---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。将 PDF Document 中指定页面的指定图像替换为另一张图像"
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

用另一张图像替换 PDF 文档指定页面上的指定图像。

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 要替换图像的页码 |
| index | Int32 | 必须替换的图像对象索引 |
| imageFile | String | 将用于替换的图像文件 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


