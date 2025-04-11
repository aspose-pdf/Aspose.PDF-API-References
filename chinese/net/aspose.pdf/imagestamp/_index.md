---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp class. 代表一个图形印章
type: docs
weight: 5930
url: /zh/net/aspose.pdf/imagestamp/
---
## ImageStamp class

代表一个图形印章。

```csharp
public sealed class ImageStamp : Stamp
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | 初始化 `ImageStamp` 类的新实例。 |
| [ImageStamp](imagestamp/#constructor_1)(string) | 通过指定文件中的图像创建图像印章。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | 获取或设置图像印章的替代文本。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 设置或获取一个布尔值，指示内容是否作为背景印章。如果值为 true，则印章内容位于底部。默认值为 false，印章内容位于顶部。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 获取或设置印章的底部边距。 |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | 获取或设置图像高度。设置此图像允许垂直缩放图像。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 获取或设置印章在页面上的水平对齐方式。 |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | 获取用于印章的图像流。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 获取或设置印章的左边距。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 获取或设置一个值以指示印章的不透明度。值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 获取或设置一个值以指示印章轮廓的不透明度。值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 获取或设置印章轮廓宽度的值。默认值为 1.0。 |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | 获取或设置图像印章的质量（以百分比表示）。有效值为 0..100%。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 获取或设置印章的右边距。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 设置或获取印章内容的旋转，依据 [`Rotation`](../rotation/) 值。注意：此属性用于设置 90 度的倍数角度（0、90、180、270 度）。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 获取或设置印章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 获取或设置印章的顶部边距。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 获取或设置印章在页面上的垂直对齐方式。 |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | 获取或设置图像宽度。设置此属性允许水平缩放图像。 |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | 获取和设置水平印章坐标，从左侧开始。 |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | 获取和设置垂直印章坐标，从底部开始。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 印章的缩放因子。允许缩放印章。请注意，ZoomX 和 ZoomY 属性对每个轴分别设置缩放因子。设置此属性会更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 印章的水平缩放因子。允许水平缩放印章。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 印章的垂直缩放因子。允许垂直缩放印章。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 返回印章 ID。 |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | 在页面上添加图形印章。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 设置印章 ID。 |

### 另请参见

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)