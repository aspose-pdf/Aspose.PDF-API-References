---
title: "TableAbsorber Class"
linktitle: "TableAbsorber"
articleTitle: "TableAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TableAbsorber class. Represents an absorber object of table elements. Performs search and provides access to search results via collection."
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

## Constructors

| Name | Description |
| --- | --- |
| [TableAbsorber](./tableabsorber/#constructor) | Initializes a new instance of the [`TableAbsorber`](../../aspose.pdf.text/tableabsorber/). |
| [TableAbsorber](./tableabsorber/#constructor_1)(*[TextSearchOptions](../../aspose.pdf.text/textsearchoptions/)*) | Initializes a new instance of the [`TableAbsorber`](../../aspose.pdf.text/tableabsorber/) with text search options. |

## Properties

| Name | Description |
| --- | --- |
| [TableList](./tablelist/) { get; } | Returns readonly IList containing tables that were found. |
| [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets text search options. |
| [UseFlowEngine](./useflowengine/) { get; set; } | * Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of. |

## Methods

| Name | Description |
| --- | --- |
| [Remove](./remove/)(*AbsorbedTable*) | Removes an [`AbsorbedTable`](../../aspose.pdf.text/absorbedtable/) from the page. |
| [Replace](./replace/)(*Page, AbsorbedTable, Table*) | Replaces an [`AbsorbedTable`](../../aspose.pdf.text/absorbedtable/) with [`Table`](../../aspose.pdf/table/) on the page. |
| [Visit](./visit/)(*Page*) | Extracts tables on the specified page. |
| [Visit](./visit/)(*Document*) | Extracts tables in the specified document. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

