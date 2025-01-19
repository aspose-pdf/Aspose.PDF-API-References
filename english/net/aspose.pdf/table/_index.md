---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table class. Represents a table that can be added to the page
type: docs
weight: 9220
url: /net/aspose.pdf/table/
---
## Table class

Represents a table that can be added to the page.

```csharp
public sealed class Table : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [Table](table/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Gets or sets the table alignment. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Gets or sets table background color |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Gets or sets the border. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Gets or sets break text for table |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Gets or sets table vertial broken; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Gets or sets the table column adjustment. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Gets the column widths of the table. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Gets or sets the styles of the border corners |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Gets default cell border; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Gets or sets the default cell padding. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Gets default cell border; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Gets or sets border included in column widhts. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Gets or sets the table is broken - will be truncated for next page. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Gets or sets the table left coordinate. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Gets or sets the maximum columns count for table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Gets the first rows count repeated for several pages |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Gets the style for repeating rows |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Gets the rows of the table. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Gets or sets the table top coordinate. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clone the table. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Get height. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Get width. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Imports one-dimensional array of data into table. Import goes one cell per each array's item and starts from row and column defined in parameters. During import, if detected that necessary rows are still absent(i.e. target table is too small to absorb all data), necessary rows will be created |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Imports data from System.Data.DataTable into Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Imports a DataTable object into the table. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Imports a DataTable object, but not as whole entity. Only specified rows and columns are imported. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Imports a DataView object's data into the table. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Set height. |

### See Also

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


