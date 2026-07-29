---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建 squarecircle 注释"
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

创建方形-圆形注释。

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| clr | Color | 方形或圆形的颜色。 |
| 方形 | Boolean | True (square)，false (circle)。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| borderWidth | Int32 | 方形或圆形的边框宽度。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


