---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph 类。表示图形生成器段落
type: docs
weight: 3940
url: /zh/net/aspose.pdf.drawing/graph/
---
## 图类

表示图形 - 图形生成器段落。

```csharp
public sealed class Graph : BaseParagraph
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | 初始化 `Graph` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | 获取或设置边框。 |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | 获取或设置一个 [`GraphInfo`](./graphinfo/) 对象，该对象指示图形信息，如颜色、线宽等。 |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | 获取或设置一个浮点值，指示图形高度。单位为点。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | 获取或设置处理段落后是否更改当前位置信息。（默认值为 true） |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | 获取或设置表格左坐标。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | 获取或设置一个 [`Shapes`](./shapes/) 集合，指示图形中的所有形状。 |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | 获取或设置一个字符串值，指示图形的标题。 |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | 获取或设置表格顶部坐标。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | 获取或设置一个浮点值，指示图形宽度。单位为点。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | 克隆图形。 |

### 另请参阅

* 类 [BaseParagraph](../../aspose.pdf/baseparagraph/)
* 命名空间 [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* 程序集 [Aspose.PDF](../../)