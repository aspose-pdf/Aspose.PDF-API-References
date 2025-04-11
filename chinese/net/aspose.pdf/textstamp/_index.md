---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp 类。表示文本印章
type: docs
weight: 11080
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
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | 如果启用，字体大小将自动调整以适应大小为：[`Width`](./width/) 和 [`Height`](./height/) 的印章矩形。默认宽度和高度来自页面矩形。 |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | 设置或获取一个布尔值，指示内容作为背景印章。如果值为 true，则印章内容位于底部。默认值为 false，印章内容位于顶部。 |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | 获取或设置印章的底部边距。 |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | 此属性确定印章在页面上的绘制方式。如果 Draw = true，印章作为图形操作绘制；如果 Draw = false，则印章作为文本绘制。 |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | 印章放置后的实际字体大小。（如果启用了 'AutoAdjustFontSizeToFitStampRectangle' 选项，可能与通过构造函数提供的初始字体大小不同。） |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | 印章在页面上的期望高度。 |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | 获取或设置印章在页面上的水平对齐方式。 |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | 定义文本对齐方式。如果此属性设置为 true，则文本的左右边缘对齐。默认值：false。 |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | 获取或设置印章的左边距。 |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | WordWrap 选项的最大行高度。 |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | 获取或设置定义字体不包含请求字符时的行为的模式。 |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | 获取或设置一个值以指示印章的不透明度。值范围从 0.0 到 1.0。默认值为 1.0。 |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | 获取或设置一个值以指示印章轮廓的不透明度。值范围从 0.0 到 1.0。默认值为 1.0。 |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | 获取或设置印章轮廓宽度的值。默认值为 1.0。 |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | 获取或设置用于替换的字体，如果用户字体不包含所需字符。 |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | 获取或设置印章的右边距。 |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | 根据 [`Rotation`](../rotation/) 值设置或获取印章内容的旋转。注意：此属性用于设置 90 度的倍数角度（0、90、180、270 度）。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | 获取或设置印章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。 |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | 定义文本的缩放。如果此属性设置为 true 并且指定了 Width 值，则文本将被缩放以适应指定的宽度。 |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | 印章内文本的对齐方式。 |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | 获取印章的文本属性。有关详细信息，请参见 [`TextState`](./textstate/)。 |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | 获取或设置印章的顶部边距。 |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | 定义放置文本的坐标原点。如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。 |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | 获取或设置用作页面上印章的字符串值。 |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | 获取或设置印章在页面上的垂直对齐方式。 |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | 印章在页面上的期望宽度。 |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | 获取或设置文本渲染的换行模式。 |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | 从左侧开始的水平印章坐标。 |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | 从底部开始的垂直印章坐标。 |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | 印章的缩放因子。允许缩放印章。请注意，ZoomX 和 ZoomY 属性对每个轴分别设置缩放因子。设置此属性会更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。 |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | 印章的水平缩放因子。允许水平缩放印章。 |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | 印章的垂直缩放因子。允许垂直缩放印章。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | 返回印章 ID。 |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | 在页面上添加文本印章。 |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | 设置印章 ID。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | 如果字体不包含所需字符，则执行的操作。 |

### 另请参见

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)