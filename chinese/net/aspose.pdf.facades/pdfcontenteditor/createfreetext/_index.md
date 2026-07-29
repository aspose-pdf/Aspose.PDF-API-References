---
title: "PdfContentEditor.CreateFreeText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 在 PDF 文档中创建自由文本注释。"
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

在 PDF 文档中创建自由文本注释

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| 页面 | Int32 | 将创建文本注释的原始页码。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


