---
title: "HtmlDiffOutputGenerator Class"
linktitle: "HtmlDiffOutputGenerator"
articleTitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for .NET"
description: "Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark."
type: docs
weight: 90
url: "/net/aspose.pdf.comparison/htmldiffoutputgenerator/"
keywords: "HtmlDiffOutputGenerator, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## HtmlDiffOutputGenerator class

Represents a class for generating html representation of texts differences.
 Deleted line breaks are indicated by paragraph mark.

```csharp
public class HtmlDiffOutputGenerator : IStringOutputGenerator, IFileOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/#constructor) | Creates an instance of [`HtmlDiffOutputGenerator`](../../aspose.pdf.comparison/htmldiffoutputgenerator/) class. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/#constructor_1)(*[OutputTextStyle](../../aspose.pdf.comparison/outputtextstyle/)*) | Creates an instance of [`HtmlDiffOutputGenerator`](../../aspose.pdf.comparison/htmldiffoutputgenerator/) class. |

## Properties

| Name | Description |
| --- | --- |
| [DeleteStyle](./deletestyle/) { get; set; } | Gets and sets the CSS-style string for Delete operation. |
| [EqualStyle](./equalstyle/) { get; set; } | Gets and sets the CSS-style string for Equal operation. |
| [InsertStyle](./insertstyle/) { get; set; } | Gets and sets the CSS-style string for Insert operation. |
| [StrikethroughDeleted](./strikethroughdeleted/) { get; set; } | Get or set text-decoration: line-through style for the delete operation. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](./generateoutput/)(*List<DiffOperation>*) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(*List<List<DiffOperation>>*) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(*List<DiffOperation>, string*) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(*List<List<DiffOperation>>, string*) | Generates the output based on the differences between texts and saves it to a file. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

