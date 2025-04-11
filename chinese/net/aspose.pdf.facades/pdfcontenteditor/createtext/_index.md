---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建 PDF 文档中的文本注释
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText 方法

在 PDF 文档中创建文本注释

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 定义注释在页面上位置的注释矩形。 |
| title | 字符串 | 注释的标题。 |
| contents | 字符串 | 注释的内容。 |
| open | 布尔值 | 一个标志，指定注释是否应最初显示为打开状态。 |
| icon | 字符串 | 用于显示注释的图标名称。此值可以是：“Comment”，“Key”，“Note”，“Help”，“NewParagraph”，“Paragraph”，“Insert” |
| page | Int32 | 将创建文本注释的原始页面编号。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)