---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。 在 PDF 文档中创建弹出注释
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup 方法

在 PDF 文档中创建弹出注释。

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 定义注释在页面上位置的注释矩形。 |
| contents | 字符串 | 注释的内容。 |
| open | 布尔值 | 一个标志，指定弹出注释是否应最初显示为打开。 |
| page | Int32 | 注释将被创建的原始页面的编号。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 另请参见

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)