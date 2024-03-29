---
title: TextFragmentState
second_title: Aspose.PDF for .NET API 参考
description: 表示文本片段的文本状态
type: docs
weight: 7130
url: /zh/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

表示文本片段的文本状态。

```csharp
public sealed class TextFragmentState : TextState
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | 初始化[`TextFragmentState`](../textfragmentstate)指定的对象[`TextFragment`](../textfragment)object. 这个[`TextFragmentState`](../textfragmentstate)不支持初始化。 TextFragmentState 仅适用于[`TextState`](../textfragment/textstate)属性. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | 设置文本的背景颜色，由[`TextFragment`](../textfragment)object |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | 获取或设置文本的字符间距，由[`TextFragment`](../textfragment)对象. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | 获取或设置文本矩形边框是否绘制标志。 |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | 获取或设置文本的字体，由[`TextFragment`](../textfragment)object |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | 获取或设置文本的字体大小，由[`TextFragment`](../textfragment)object |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | 设置文本的字体样式，由[`TextFragment`](../textfragment)object |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | 获取或设置文本的前景色，由[`TextFragment`](../textfragment)object |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | 获取或设置格式化选项。 选项的设置仅在生成器场景中有效。 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | 获取或设置文本的水平对齐方式。 |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | 获取或设置文本的水平缩放，由[`TextFragment`](../textfragment)对象. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | 获取或设置文本的不可见性。 |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | 获取或设置文本的行距。 |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | 获取或设置文本的渲染模式。 |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | 获取或设置以度为单位的旋转角度。 |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | 为文本设置删除线，由[`TextFragment`](../textfragment)object |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | 获取或设置颜色描边操作[`TextFragment`](../textfragment)渲染（描边文本，矩形边框） |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | 获取或设置文本的下标，由[`TextFragment`](../textfragment)对象. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | 获取或设置文本的上标，由[`TextFragment`](../textfragment)对象. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | 获取文本的制表位。 |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | 获取或设置文本的下划线，由[`TextFragment`](../textfragment)object |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | 获取或设置文本的字间距。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | 应用来自另一个 textState 的设置。 |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | 测量字符串。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | 默认字体的空格字符宽度制表的默认值。 |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | 您可以将此标记放在文本中以声明制表。 |

### 评论

提供了一种更改文本以下属性的方法： font ([`Font`](./font)属性） 字体大小（[`FontSize`](./fontsize)属性） 字体样式（[`FontStyle`](./fontstyle)属性） 前景色（[`ForegroundColor`](./foregroundcolor)属性） 背景颜色（[`BackgroundColor`](./backgroundcolor)属性) 注意改变[`TextFragmentState`](../textfragmentstate)属性可能会改变内部[`Segments`](../textfragment/segments)集合，因为 TextFragment 是一个聚合对象 并且它可能会重新排列内部段或将它们合并为单个段。 如果您的要求是离开[`Segments`](../textfragment/segments)集合不变，请单独更改内部段。

### 例子

该示例演示了如何更改文本的颜色和字体大小[`TextState`](../textstate)对象.

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一个文本出现的前景色
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 更改第一个文本出现的字体大小
absorber.TextFragments[1].TextState.FontSize = 15;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
