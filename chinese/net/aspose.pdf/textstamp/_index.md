---
title: "类 TextStamp"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.TextStamp 类。表示文本印章"
type: docs
weight: 11270
url: /zh/net/aspose.pdf/textstamp/
---
## TextStamp class

表示文本印章。

```csharp
public class TextStamp : Stamp
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | 使用 formattedText 对象初始化 `TextStamp` 类的新实例 |
| [TextStamp](textstamp/#constructor_1)(string) | 初始化 `TextStamp` 类的新实例。 |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | 初始化 `TextStamp` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | 自动调整字体大小精度。默认值：0.1； |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 如果启用，字体大小将自动调整以适应印章矩形的尺寸：[`Width`](./width/) 和 [`Height`](./height/)。默认宽度和高度取自页面矩形。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 设置或获取一个布尔值，指示内容是否作为背景进行印章。如果值为 true，印章内容位于底部。默认情况下，值为 false，印章内容位于顶部。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 获取或设置印章的底部边距。 |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | 此属性决定印章在页面上的绘制方式。如果 Draw = true，印章将以图形操作符绘制；如果 Draw = false，则印章以文本方式绘制。 |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | 印章放置后实际的字体大小。（如果启用了 'AutoAdjustFontSizeToFitStampRectangle' 选项，可能会与通过构造函数提供的初始字体大小不同。） |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | 页面上印章的期望高度。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 获取或设置印章在页面上的水平对齐方式。 |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | 定义文本对齐方式。如果此属性设为 true，文本的左、右边缘将对齐。默认值：false。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 获取或设置印章的左侧边距。 |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap 选项的最大行高。 |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | 获取或设置在字体不包含所需字符时定义行为的模式。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 获取或设置一个值以指示印章的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 获取或设置一个值以指示印章轮廓的不透明度。该值范围为 0.0 到 1.0。默认值为 1.0。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 获取或设置印章轮廓宽度的值。默认值为 1.0。 |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | 获取或设置在用户字体不包含所需字符时用于替换的字体。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 获取或设置印章的右边距。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 设置或获取印章内容的旋转，依据 [`Rotation`](../rotation/) 值。注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。若要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 获取或设置印章的旋转角度（单位：度）。此属性允许设置任意旋转角度。 |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | 定义文本的缩放。如果此属性设为 true 且指定了 Width 值，文本将按比例缩放以适应指定宽度。 |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | 印章内部文本的对齐方式。 |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | 获取印章的文本属性。详情请参阅 [`TextState`](./textstate/)。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 获取或设置印章的上边距。 |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | 定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。 |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | 获取或设置在页面上用作印章的字符串值。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 获取或设置印章在页面上的垂直对齐方式。 |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | 印章在页面上的期望宽度。 |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | 获取或设置文本渲染的自动换行模式。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 印章的水平坐标，起始于左侧。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 印章的垂直坐标，起始于底部。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 印章的缩放因子。用于缩放印章。请注意，ZoomX 和 ZoomY 两个属性可以分别为每个轴设置缩放因子。设置此属性会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 的值。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 印章的水平缩放因子。用于水平缩放印章。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 印章的垂直缩放因子。用于垂直缩放印章。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 返回印章 ID。 |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | 在页面上添加文本印章。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 设置印章 Id。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | 当字体不包含所需字符时执行的操作。 |

### 另请参见

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


