---
title: CreateText
second_title: Aspose.PDF for .NET API 参考
description: 在 PDF 文档中创建文本注释
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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 定义页面上注释位置的注释矩形。 |
| title | String | 注释的标题。 |
| contents | String | 注释的内容。 |
| open | Boolean | 一个标志，指定注释最初是否应打开显示。 |
| icon | String | 图标的名称将用于显示注释。 这个值可以是：“注释”、“键”、“注释”、“帮助”、“新建段落”、“段落”、“插入” |
| page | Int32 | 将在其中创建文本注释的原始页数。 |

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->