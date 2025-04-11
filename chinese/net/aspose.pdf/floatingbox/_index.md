---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox 类。
type: docs
weight: 4870
url: /zh/net/aspose.pdf/floatingbox/
---
## FloatingBox 类

```csharp
public class FloatingBox : BaseParagraph
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | 初始化 `FloatingBox` 类的新实例。 |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | 使用指定的宽度和高度初始化 `FloatingBox` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | 获取或设置一个 [`Color`](../color/) 对象，表示浮动框的背景颜色。 |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | 获取或设置页面的背景图像（仅供生成器使用，读取文档时不填充）。 |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | 获取或设置一个 [`BorderInfo`](../borderinfo/) 对象，表示浮动框的边框信息。 |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | 获取或设置列信息 |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | 获取或设置一个浮动值，表示浮动框的高度。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否位于下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | 获取或设置一个布尔值，指示段落是否需要在下一页重复。默认值为 false。该属性仅在段落本身和其 ReferenceParagraphID 所引用的对象都包含在 RepeatingRows 中时有效。 |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | 获取或设置表格的左坐标。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | 获取或设置一个 [`MarginInfo`](../margininfo/) 对象，表示浮动框的内边距。 |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | 获取或设置一个 [`Paragraphs`](./paragraphs/) 集合，表示单元格中的所有段落。 |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | 指定用于确定浮动框在页面上位置的变体。 |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | 获取或设置表格的顶部坐标。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | 获取或设置一个浮动值，表示浮动框的宽度。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，表示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | 克隆一个新的 `FloatingBox` 对象。浮动框中的段落不会被克隆。 |

### 另请参见

* 类 [BaseParagraph](../baseparagraph/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)