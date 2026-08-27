---
title: "PdfContentEditor.CreatePolygon"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建多边形注释"
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

创建多边形注释。

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 另请参见

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


