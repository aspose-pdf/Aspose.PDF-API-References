---
title: "类 FloatingBox"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.FloatingBox 类。"
type: docs
weight: 4990
url: /zh/net/aspose.pdf/floatingbox/
---
## FloatingBox class

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
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | 获取或设置一个指示浮动框背景颜色的 [`Color`](../color/) 对象。 |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | 获取或设置页面的背景图像（仅用于生成器，在读取文档时不填充）。 |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | 获取或设置一个指示浮动框边框信息的 [`BorderInfo`](../borderinfo/) 对象。 |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | 获取或设置列信息 |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | 获取或设置指示浮动框高度的浮点值。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | 获取或设置一个布尔值，指示段落是否需要在下一页重复。默认值为 false。该属性仅在段落本身以及其 ReferenceParagraphID 所引用的对象均包含在 RepeatingRows 中时有效。 |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | 获取或设置表格的左坐标。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | 获取或设置一个指示浮动框内边距的 [`MarginInfo`](../margininfo/) 对象。 |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | 获取或设置一个指示单元格中所有段落的 [`Paragraphs`](./paragraphs/) 集合。 |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | 指定用于确定 FloatingBox 在页面上位置的变体。 |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | 获取或设置表格的顶部坐标。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | 获取或设置指示浮动框宽度的浮点值。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | 克隆一个新的 `FloatingBox` 对象。浮动框中的段落不会被克隆。 |

### 另请参见

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


