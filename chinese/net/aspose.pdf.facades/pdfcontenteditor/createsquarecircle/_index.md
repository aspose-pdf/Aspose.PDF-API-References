---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建方形圆形注释
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle 方法

创建方形圆形注释。

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 定义注释在页面上位置的注释矩形。 |
| contents | 字符串 | 注释的内容。 |
| clr | 颜色 | 方形或圆形的颜色。 |
| square | 布尔值 | 真（方形），假（圆形）。 |
| page | Int32 | 注释将被创建的原始页面编号。 |
| borderWidth | Int32 | 方形或圆形的边框宽度。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)