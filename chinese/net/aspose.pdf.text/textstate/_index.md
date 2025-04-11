---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextState 类。表示文本的文本状态
type: docs
weight: 11070
url: /zh/net/aspose.pdf.text/textstate/
---
## TextState 类

表示文本的文本状态

```csharp
public class TextState
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextState](textstate/#constructor)() | 创建文本状态对象。 |
| [TextState](textstate/#constructor_2)(Color) | 创建具有前景色规格的文本状态对象。 |
| [TextState](textstate/#constructor_1)(double) | 创建具有字体大小规格的文本状态对象。 |
| [TextState](textstate/#constructor_4)(string) | 创建具有字体系列规格的文本状态对象。 |
| [TextState](textstate/#constructor_3)(Color, double) | 创建具有前景色和字体大小规格的文本状态对象。 |
| [TextState](textstate/#constructor_6)(string, double) | 创建具有字体系列和字体大小规格的文本状态对象。 |
| [TextState](textstate/#constructor_5)(string, bool, bool) | 创建具有字体系列和字体样式规格的文本状态对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | 设置文本的背景色。 |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | 获取或设置文本的字符间距。 |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | 获取或设置文本的坐标原点。如果 CoordinateOrigin 是 Descender，则文本的 Y 坐标对应于字体的最低点。如果 CoordinateOrigin 是 BaseLine，则文本的 Y 坐标对应于字体的基线。默认值为 Descender。如果字体的 Descent 值过大，文本可能会比其他字体渲染得更高。在这种情况下，可以选择 CoordinateOrigin BaseLine 以获得更好的文本渲染。 |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | 获取或设置文本的字体。 |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | 获取或设置文本的字体大小。 |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | 设置文本的字体样式。 |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | 获取或设置文本的前景色。 |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | 获取或设置文本的水平对齐方式。 |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | 获取或设置文本的水平缩放。 |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | 获取或设置文本的不可见性。这基本上反映了 [`RenderingMode`](./renderingmode/) 状态，除了某些特殊情况（如剪裁）。 |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | 获取或设置文本的行间距。 |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | 获取或设置文本的渲染模式。 |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | 获取或设置文本的删除线，由 [`TextSegment`](../textsegment/) 对象表示 |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | 获取或设置文本的前景色。 |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | 获取或设置文本的下标。 |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | 获取或设置文本的上标。 |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | 获取或设置文本的下划线，由 [`TextFragment`](../textfragment/) 对象表示 |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | 获取或设置文本的字间距。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | 从另一个 textState 应用设置。 |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | 测量字符高度。 |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | 测量字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | 默认字体的空格字符宽度的制表符默认值。 |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | 您可以在文本中放置此标签以声明制表符。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)