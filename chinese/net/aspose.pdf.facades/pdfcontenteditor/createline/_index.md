---
title: "PdfContentEditor.CreateLine"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建线注释。"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

创建线条注释。

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| x1 | Single | 线的起始水平坐标。 |
| y1 | Single | 线的起始垂直坐标。 |
| x2 | Single | 线的结束水平坐标。 |
| y2 | Single | 线的结束垂直坐标。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| border | Int32 | 边框宽度（单位为点）。如果此值为 0，则不绘制边框。默认值为 1。 |
| clr | Color | 线的颜色。 |
| borderStyle | String | 指定绘制线条时使用的宽度和虚线模式的边框样式。该值可以是："S"（实线），"D"（虚线），"B"（斜面），"I"（内嵌），"U"（下划线）。 |
| dashArray | Int32[] | 定义用于绘制虚线边框的虚线和间隙模式的数组。如果使用此属性，borderSyle 必须相应设置为 "D"。 |
| LEArray | String[] | 一个包含两个值的数组，分别指定绘制线条的起始和结束样式。可用的值有："Square"、"Circle"、"Diamond"、"OpenArrow"、"ClosedArrow"、"None"、"Butt"、"ROpenArrow"、"RClosedArrow"、"Slash"。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


