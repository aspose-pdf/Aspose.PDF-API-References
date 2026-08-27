---
title: "PdfContentEditor.DrawCurve"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建曲线注释"
type: docs
weight: 360
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

创建曲线注释。

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo 类的实例。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| annotRect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| annotContents | String | 注释的内容。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 另请参见

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


