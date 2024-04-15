---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber class. Represents an absorber object of table elements. Performs search and provides access to search results via TableList collection
type: docs
weight: 8370
url: /net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Represents an absorber object of table elements. Performs search and provides access to search results via [`TableList`](./tablelist/) collection.

```csharp
public class TableAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Initializes a new instance of the `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Initializes a new instance of the `TableAbsorber` with text search options. |

## Properties

| Name | Description |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Returns readonly IList containing tables that were found |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Gets or sets text search options. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders. Doesn't support editing tables and getting text styles yet. Default value is false; |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Removes an [`AbsorbedTable`](../absorbedtable/) from the page. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Replaces an [`AbsorbedTable`](../absorbedtable/) with [`Table`](../../aspose.pdf/table/) on the page. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extracts tables in the specified document. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extracts tables on the specified page |

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

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


