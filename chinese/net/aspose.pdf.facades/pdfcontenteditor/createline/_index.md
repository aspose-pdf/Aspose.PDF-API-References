---
title: CreateLine
second_title: Aspose.PDF for .NET API 参考
description: 创建线注释
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

创建线注释。

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 定义页面上注释位置的注释矩形。 |
| contents | String | 注释的内容。 |
| x1 | Single | 线的起始水平坐标。 |
| y1 | Single | 线的起始垂直坐标。 |
| x2 | Single | 线的结束水平坐标。 |
| y2 | Single | 线的结束垂直坐标。 |
| page | Int32 | 将在其中创建注释的原始页数。 |
| border | Int32 | 以磅为单位的边框宽度。如果此值为 0，则不绘制边框。默认值为 1。 |
| clr | Color | 线的颜色。 |
| borderStyle | String | 指定用于绘制线条的宽度和虚线图案的边框样式。 此值可以是：“S”（实线）、“D”（虚线）、“B”（斜角）、“I”（插图） , “U”（下划线）。 |
| dashArray | Int32[] | 一个虚线数组，定义用于绘制虚线边框的虚线和间隙模式。 如果使用它，borderSyle 必须相应地设置为“D”。 |
| LEArray | String[] | 两个值的数组，分别指定绘制线的开始和结束样式。 值可以是：“Square”、“Circle”、“Diamond”、“OpenArrow”、“ClosedArrow”、“None”、“Butt” 、“ROpenArrow”、“RClosedArrow”、“Slash”。 |

### 例子

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfContentEditor](../../pdfcontenteditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfcontenteditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
