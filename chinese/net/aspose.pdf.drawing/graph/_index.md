---
title: Graph
second_title: Aspose.PDF for .NET API 参考
description: 表示图形 - 图形生成器段落
type: docs
weight: 1990
url: /zh/net/aspose.pdf.drawing/graph/
---
## Graph class

表示图形 - 图形生成器段落。

```csharp
public sealed class Graph : BaseParagraph
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Graph](graph)(float, float) | 初始化[`Graph`](../graph)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border) { get; set; } | 获取或设置边框。 |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo) { get; set; } | 获取或设置一个[`GraphInfo`](./graphinfo)表示图形信息的对象，例如颜色， 线宽等 |
| [Height](../../aspose.pdf.drawing/graph/height) { get; set; } | 获取或设置表示图形高度的浮点值。 单位为点。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | 获取或设置段落 的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition) { get; set; } | 获取或设置进程段落后更改当前位置。（默认为真） |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Left](../../aspose.pdf.drawing/graph/left) { get; set; } | 获取或设置表格左坐标。 |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Shapes](../../aspose.pdf.drawing/graph/shapes) { get; set; } | 获取或设置一个[`Shapes`](./shapes)表示图中所有形状的集合。 |
| [Title](../../aspose.pdf.drawing/graph/title) { get; set; } | 获取或设置表示图形标题的字符串值。 |
| [Top](../../aspose.pdf.drawing/graph/top) { get; set; } | 获取或设置桌面坐标 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | 获取或设置段落 的垂直对齐方式 |
| [Width](../../aspose.pdf.drawing/graph/width) { get; set; } | 获取或设置表示图形宽度的浮点值。 单位为点。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone)() | 克隆图。 |

### 也可以看看

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* 命名空间 [Aspose.Pdf.Drawing](../../aspose.pdf.drawing)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->