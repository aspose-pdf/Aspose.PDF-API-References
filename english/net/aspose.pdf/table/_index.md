---
title: "Table Class"
linktitle: "Table"
articleTitle: "Table"
second_title: "Aspose.PDF for .NET"
description: "Represents a table that can be added to the page."
type: docs
weight: 2940
url: "/net/aspose.pdf/table/"
keywords: "Table, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Table class

Represents a table that can be added to the page.

```csharp
public sealed class Table : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [Table](./table/#constructor) | Initializes a new instance of the Table class. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](./alignment/) { get; set; } | Gets or sets the table alignment. |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Gets or sets table background color. |
| [Border](./border/) { get; set; } | Gets or sets the border. |
| [BreakText](./breaktext/) { get; set; } | Gets or sets break text for table. |
| [Broken](./broken/) { get; set; } | Gets or sets table vertial broken;. |
| [ColumnAdjustment](./columnadjustment/) { get; set; } | Gets or sets the table column adjustment. |
| [ColumnWidths](./columnwidths/) { get; set; } | Gets the column widths of the table. |
| [CornerStyle](./cornerstyle/) { get; set; } | Gets or sets the styles of the border corners. |
| [DefaultCellBorder](./defaultcellborder/) { get; set; } | Gets default cell border;. |
| [DefaultCellPadding](./defaultcellpadding/) { get; set; } | Gets or sets the default cell padding. |
| [DefaultCellTextState](./defaultcelltextstate/) { get; set; } | Gets or sets the default cell text state. |
| [DefaultColumnWidth](./defaultcolumnwidth/) { get; set; } | Gets default cell border;. |
| [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph. *(Inherited from BaseParagraph)* |
| [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). *(Inherited from BaseParagraph)* |
| [IsBordersIncluded](./isbordersincluded/) { get; set; } | Gets or sets border included in column widhts. |
| [IsBroken](./isbroken/) { get; set; } | Gets or sets the table is broken - will be truncated for next page. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. *(Inherited from BaseParagraph)* |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. *(Inherited from BaseParagraph)* |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. *(Inherited from BaseParagraph)* |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. *(Inherited from BaseParagraph)* |
| [Left](./left/) { get; set; } | Gets or sets the table left coordinate. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation). *(Inherited from BaseParagraph)* |
| [RepeatingColumnsCount](./repeatingcolumnscount/) { get; set; } | Gets or sets the maximum columns count for table. |
| [RepeatingRowsCount](./repeatingrowscount/) { get; set; } | Gets the first rows count repeated for several pages. |
| [RepeatingRowsStyle](./repeatingrowsstyle/) { get; set; } | Gets the style for repeating rows. |
| [Rows](./rows/) { get; } | Gets the rows of the table. |
| [Top](./top/) { get; set; } | Gets or sets the table top coordinate. |
| [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph. *(Inherited from BaseParagraph)* |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex. *(Inherited from BaseParagraph)* |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) | Clone the table. |
| [GetHeight](./getheight/)(*Page*) | Get height. |
| [GetWidth](./getwidth/) | Get width. |
| [ImportArray](./importarray/)(*object[], int, int, bool*) | Imports one-dimensional array of data into table. Import goes one cell per each array's item and. |
| [ImportDataTable](./importdatatable/)(*DataTable, bool, int, int*) | Imports data from System.Data.DataTable into Aspose.Pdf.Table. |
| [ImportDataTable](./importdatatable/)(*DataTable, bool, int, byte, int, int, bool*) | Imports a `DataTable` object into the table. |
| [ImportDataTable](./importdatatable/)(*DataTable, int[], int[], int, int, bool, bool*) | Imports a `DataTable` object, but not as whole entity. Only specified rows and columns are imported. |
| [ImportDataView](./importdataview/)(*DataView, bool, int, int, int, int*) | Imports a `DataView` object's data into the table. |
| [SetColumnTextState](./setcolumntextstate/)(*int, TextState*) | Set height. |

### See Also

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

