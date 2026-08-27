---
title: "类 PdfPageStamp"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfPageStamp 类。该类表示使用 PDF 页面作为印章的印章。"
type: docs
weight: 8560
url: /zh/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

表示使用 PDF 页面作为印章的类。

```csharp
public sealed class PdfPageStamp : Stamp
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp 的构造函数。 |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | 从流中的文档指定页面创建 PDF 页面印章。 |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 从指定文件中文档的指定页面创建 PDF 页面印章。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 设置或获取一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容位于底部。默认情况下，值为 false，印章内容位于顶部。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 获取或设置印章的底部边距。 |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | 页面上印章的期望高度。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 获取或设置印章在页面上的水平对齐方式。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 获取或设置印章的左侧边距。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 获取或设置一个值以指示印章的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 获取或设置一个值以指示印章轮廓的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 获取或设置印章轮廓宽度的值。默认值为 1.0。 |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | 获取或设置将用作印章的页面。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 获取或设置印章的右边距。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 设置或获取印章内容的旋转，依据 [`Rotation`](../rotation/) 值。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 获取或设置印章的旋转角度（单位：度）。此属性允许设置任意旋转角度。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 获取或设置印章的上边距。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 获取或设置印章在页面上的垂直对齐方式。 |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | 印章在页面上的期望宽度。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 印章的水平坐标，起始于左侧。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 印章的垂直坐标，起始于底部。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 印章的缩放因子。用于缩放印章。请注意，ZoomX 和 ZoomY 两个属性可以分别为每个轴设置缩放因子。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 的值。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 印章的水平缩放因子。用于水平缩放印章。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 印章的垂直缩放因子。用于垂直缩放印章。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 返回印章 ID。 |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 在指定页面上放置印章。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 设置印章 Id。 |

### 另请参见

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


