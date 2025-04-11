---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentState 类。表示文本片段的文本状态
type: docs
weight: 10970
url: /zh/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

表示文本片段的文本状态。

```csharp
public sealed class TextFragmentState : TextState
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 使用指定的 [`TextFragment`](../textfragment/) 对象初始化 `TextFragmentState` 对象的新实例。此 `TextFragmentState` 初始化不受支持。TextFragmentState 仅在 [`TextState`](../textfragment/textstate/) 属性中可用。 |

## Properties

| Name | Description |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | 设置文本的背景颜色，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | 获取或设置文本的字符间距，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | 获取或设置文本的坐标原点。如果坐标原点为 Descender，则文本 Y 坐标对应于字体的最低点。如果坐标原点为 BaseLine，则文本 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的降部值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择坐标原点 BaseLine 以获得更好的文本渲染。 |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | 获取或设置文本矩形边框绘制标志。 |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | 获取或设置文本的字体，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | 获取或设置文本的字体大小，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | 设置文本的字体样式，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | 获取或设置文本的前景颜色，由 [`TextFragment`](../textfragment/) 对象表示 |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 获取或设置格式选项。选项的设置仅在生成器场景中有效。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | 获取或设置文本的水平对齐方式。 |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | 获取或设置文本的水平缩放，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | 获取或设置文本的不可见性。 |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | 获取或设置文本的行间距。 |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | 获取或设置文本的渲染模式。 |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 获取或设置旋转角度（以度为单位）。 |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | 获取或设置文本的删除线，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | 获取或设置 [`TextFragment`](../textfragment/) 渲染的颜色描边操作（描边文本，矩形边框） |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | 获取或设置文本的下标，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | 获取或设置文本的上标，由 [`TextFragment`](../textfragment/) 对象表示。 |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | 获取文本的制表位。 |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | 获取或设置文本的下划线，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | 获取或设置文本的字间距。 |

## Methods

| Name | Description |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 从另一个 textState 应用设置。 |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 检查输入字符串是否可以放置在定义的矩形内。 |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 测量字符高度。（2 个方法） |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 测量字符串。 |

## Fields

| Name | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 默认字体的空格字符宽度的制表符默认值。 |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | 您可以在文本中放置此标签以声明制表符。 |

## Remarks

提供了一种更改文本以下属性的方法：字体 ([`Font`](./font/) 属性) 字体大小 ([`FontSize`](./fontsize/) 属性) 字体样式 ([`FontStyle`](./fontstyle/) 属性) 前景颜色 ([`ForegroundColor`](./foregroundcolor/) 属性) 背景颜色 ([`BackgroundColor`](./backgroundcolor/) 属性) 请注意，更改 `TextFragmentState` 属性可能会更改内部 [`Segments`](../textfragment/segments/) 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的要求是保持 [`Segments`](../textfragment/segments/) 集合不变，请单独更改内部段。

## Examples

该示例演示如何使用 [`TextState`](../textstate/) 对象更改文本的颜色和字体大小。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)