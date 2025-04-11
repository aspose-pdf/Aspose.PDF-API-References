---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table 类。表示可以添加到页面的表格
type: docs
weight: 10280
url: /zh/net/aspose.pdf/table/
---
## 表类

表示可以添加到页面的表格。

```csharp
public sealed class Table : BaseParagraph
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Table](table/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | 获取或设置表格对齐方式。 |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | 获取或设置表格背景颜色 |
| [Border](../../aspose.pdf/table/border/) { get; set; } | 获取或设置边框。 |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | 获取或设置表格的换行文本 |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | 获取或设置表格的垂直断裂； |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | 获取或设置表格列的调整。 |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | 获取表格的列宽。 |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | 获取或设置边框角的样式 |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | 获取默认单元格边框； |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | 获取或设置默认单元格内边距。 |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | 获取或设置默认单元格文本状态。 |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | 获取默认单元格边框； |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | 获取或设置边框是否包含在列宽中。 |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | 获取或设置表格是否断裂 - 将被截断到下一页。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Left](../../aspose.pdf/table/left/) { get; set; } | 获取或设置表格的左坐标。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | 获取或设置表格的最大列数 |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | 获取在多个页面上重复的第一行数 |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | 获取重复行的样式 |
| [Rows](../../aspose.pdf/table/rows/) { get; } | 获取表格的行。 |
| [Top](../../aspose.pdf/table/top/) { get; set; } | 获取或设置表格的顶部坐标。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | 克隆表格。 |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | 获取高度。 |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | 获取宽度。 |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | 将一维数据数组导入表格。导入从参数中定义的行和列开始，每个数组项对应一个单元格。在导入过程中，如果检测到必要的行仍然缺失（即目标表格太小，无法容纳所有数据），将创建必要的行 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | 从 System.Data.DataTable 导入数据到 Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | 将 DataTable 对象导入表格。 |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | 导入 DataTable 对象，但不是作为整体实体。仅导入指定的行和列。 |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | 将 DataView 对象的数据导入表格。 |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | 设置高度。 |

### 另请参阅

* 类 [BaseParagraph](../baseparagraph/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)