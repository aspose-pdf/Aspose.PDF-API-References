---
title: "类 TextFragmentState"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextFragmentState 类。表示文本片段的文本状态。"
type: docs
weight: 11150
url: /zh/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

表示文本片段的文本状态。

```csharp
public sealed class TextFragmentState : TextState
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | 使用指定的 [`TextFragment`](../textfragment/) 对象初始化 `TextFragmentState` 对象的新实例。此 `TextFragmentState` 初始化不受支持。TextFragmentState 仅在具有 [`TextState`](../textfragment/textstate/) 属性时可用。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | 设置文本的背景颜色，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | 获取或设置文本的字符间距，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | 获取或设置文本的 CoordinateOrigin。如果 CoordinateOrigin 为 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 为 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 CoordinateOrigin 为 BaseLine，以获得更好的文本渲染。 |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | 获取或设置文本矩形边框是否绘制的标志。 |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | 获取或设置文本的字体，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | 获取或设置文本的字体大小，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | 设置文本的字体样式，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | 获取或设置文本的前景颜色，由 [`TextFragment`](../textfragment/) 对象表示 |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | 获取或设置格式化选项。仅在生成器场景中设置这些选项才会生效。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | 获取或设置文本的水平对齐方式。 |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | 获取或设置文本的水平缩放，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | 获取或设置文本的不可见性。 |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | 获取或设置文本的行间距。 |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | 获取或设置文本的渲染模式。 |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | 获取或设置以度为单位的旋转角度。 |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | 获取或设置文本的删除线，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | 获取或设置 [`TextFragment`](../textfragment/) 渲染的颜色描边操作（描边文本、矩形边框） |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | 获取或设置文本的下标，由 [`TextFragment`](../textfragment/) 对象表示。 |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | 获取或设置文本的上标，由 [`TextFragment`](../textfragment/) 对象表示。 |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | 获取文本的制表位。 |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | 您可以在文本中放置此标签以声明制表符。 |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | 获取或设置文本的下划线，由 [`TextFragment`](../textfragment/) 对象表示 |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | 获取或设置文本的字间距。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | 从另一个 textState 应用设置。 |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | 检查输入字符串是否可以放置在定义的矩形内。 |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | 测量字符高度。（2 种方法） |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | 测量字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 默认字体的空格字符宽度中的制表符默认值。 |

## 备注

提供了一种更改文本以下属性的方法：字体（[`Font`](./font/) 属性）、字体大小（[`FontSize`](./fontsize/) 属性）、字体样式（[`FontStyle`](./fontstyle/) 属性）、前景颜色（[`ForegroundColor`](./foregroundcolor/) 属性）、背景颜色（[`BackgroundColor`](./backgroundcolor/) 属性）。请注意，修改 `TextFragmentState` 属性可能会更改内部 [`Segments`](../textfragment/segments/) 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的需求是保持 [`Segments`](../textfragment/segments/) 集合不变，请单独更改内部段。

## 示例

示例演示了如何使用 [`TextState`](../textstate/) 对象更改文本的颜色和字体大小。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的前景颜色
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 更改首次文本出现的字体大小
absorber.TextFragments[1].TextState.FontSize = 15;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


