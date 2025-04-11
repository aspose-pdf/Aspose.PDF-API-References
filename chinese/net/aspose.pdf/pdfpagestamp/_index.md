---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp class. 类表示使用 PDF 页面作为印章的印章
type: docs
weight: 8420
url: /zh/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

类表示使用 PDF 页面作为印章的印章。

```csharp
public sealed class PdfPageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | PdfPageStamp 的构造函数。 |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | 从流中指定文档的页面创建 Pdf 页面印章。 |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | 从指定文件中指定文档的页面创建 Pdf 页面印章。 |

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 设置或获取一个布尔值，指示内容是否作为背景被印章。如果值为 true，则印章内容位于底部。默认值为 false，印章内容位于顶部。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 获取或设置印章的底部边距。 |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | 页面上印章的期望高度。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 获取或设置印章在页面上的水平对齐方式。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 获取或设置印章的左边距。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 获取或设置一个值以指示印章的不透明度。值范围从 0.0 到 1.0。默认值为 1.0。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 获取或设置一个值以指示印章轮廓的不透明度。值范围从 0.0 到 1.0。默认值为 1.0。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 获取或设置印章轮廓宽度的值。默认值为 1.0。 |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | 获取或设置将用作印章的页面。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 获取或设置印章的右边距。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 设置或获取印章内容的旋转，依据 [`Rotation`](../rotation/) 值。注意：此属性用于设置 90 度的倍数角度（0、90、180、270 度）。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 获取或设置印章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 获取或设置印章的顶部边距。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 获取或设置印章在页面上的垂直对齐方式。 |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | 页面上印章的期望宽度。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 从左侧开始的水平印章坐标。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 从底部开始的垂直印章坐标。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 印章的缩放因子。允许缩放印章。请注意，ZoomX 和 ZoomY 属性对每个轴分别设置缩放因子。设置此属性会更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 印章的水平缩放因子。允许水平缩放印章。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 印章的垂直缩放因子。允许垂直缩放印章。 |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 返回印章 ID。 |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | 在指定页面上放置印章。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 设置印章 ID。 |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)