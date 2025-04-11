---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建线注释
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine 方法

创建线注释。

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 定义注释在页面上位置的注释矩形。 |
| contents | 字符串 | 注释的内容。 |
| x1 | 单精度 | 线的起始水平坐标。 |
| y1 | 单精度 | 线的起始垂直坐标。 |
| x2 | 单精度 | 线的结束水平坐标。 |
| y2 | 单精度 | 线的结束垂直坐标。 |
| page | Int32 | 注释将被创建的原始页面编号。 |
| border | Int32 | 边框宽度（以点为单位）。如果该值为 0，则不绘制边框。默认值为 1。 |
| clr | 颜色 | 线的颜色。 |
| borderStyle | 字符串 | 指定绘制线时使用的宽度和虚线模式的边框样式。该值可以是：“S”（实线）、“D”（虚线）、“B”（斜角）、“I”（内嵌）、“U”（下划线）。 |
| dashArray | Int32[] | 定义用于绘制虚线边框的虚线和间隙模式的虚线数组。如果使用，则 borderSyle 必须相应设置为 “D”。 |
| LEArray | 字符串[] | 一个包含两个值的数组，分别指定绘制线的起始和结束样式。值可以是：“方形”、“圆形”、“菱形”、“开放箭头”、“闭合箭头”、“无”、“平头”、“ROpenArrow”、“RClosedArrow”、“斜杠”。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)