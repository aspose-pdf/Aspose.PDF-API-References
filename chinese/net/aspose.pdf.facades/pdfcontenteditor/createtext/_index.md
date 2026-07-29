---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建 PDF 文档中的文本注释。"
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

在 PDF 文档中创建文本注释

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| title | String | 注释的标题。 |
| 内容 | String | 注释的内容。 |
| 打开 | Boolean | 一个标志，指定注释是否应在初始时显示为打开状态。 |
| icon | String | 将在显示注释时使用的图标名称。该值可以是："Comment"、"Key"、"Note"、"Help"、"NewParagraph"、"Paragraph"、"Insert"。 |
| 页面 | Int32 | 将创建文本注释的原始页码。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


