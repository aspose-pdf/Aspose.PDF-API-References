---
title: "TableAbsorber Class"
linktitle: "TableAbsorber"
articleTitle: "TableAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TableAbsorber class. Represents an absorber object of table elements. Performs search and provides access to search results via TableList col..."
type: docs
weight: 400
url: "/net/aspose.pdf.text/tableabsorber/"
keywords: "TableAbsorber, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TableAbsorber class

Represents an absorber object of table elements.
 Performs search and provides access to search results via `TableList` collection.

```csharp
public class TableAbsorber
```

## Examples

The example demonstrates how to find table on the first PDF document page and replace the text in a table cell.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

## Constructors

| Name | Description |
| --- | --- |
| [TableAbsorber](./tableabsorber/#constructor)() | Initializes a new instance of the [`TableAbsorber`](../../aspose.pdf.text/tableabsorber/). |
| [TableAbsorber](./tableabsorber/#constructor_1)(TextSearchOptions) | Initializes a new instance of the [`TableAbsorber`](../../aspose.pdf.text/tableabsorber/) with text search options. |

## Properties

| Name | Description |
| --- | --- |
| virtual [TableList](./tablelist/) { get; } | Returns readonly IList containing tables that were found |
| virtual [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets text search options. |
| [UseFlowEngine](./useflowengine/) { get; set; } | * Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders. Doesn't support editing tables and getting text styles yet. Default value is false; |

## Methods

| Name | Description |
| --- | --- |
| [Remove](./remove/)(AbsorbedTable) | Removes an [`AbsorbedTable`](../../aspose.pdf.text/absorbedtable/) from the page. |
| [Replace](./replace/)(Page, AbsorbedTable, Table) | Replaces an [`AbsorbedTable`](../../aspose.pdf.text/absorbedtable/) with [`Table`](../../aspose.pdf/table/) on the page. |
| [Visit](./visit/)(Document) | Extracts tables in the specified document. |
| virtual [Visit](./visit/)(Page) | Extracts tables on the specified page |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

