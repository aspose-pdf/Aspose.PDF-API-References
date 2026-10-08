---
title: "HtmlDiffOutputGenerator Class"
linktitle: "HtmlDiffOutputGenerator"
articleTitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. Represents a class for generating html representation of texts differences. Deleted line breaks are indi..."
type: docs
weight: 90
url: "/net/aspose.pdf.comparison/htmldiffoutputgenerator/"
keywords: "HtmlDiffOutputGenerator, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## HtmlDiffOutputGenerator class

Represents a class for generating html representation of texts differences.
 Deleted line breaks are indicated by paragraph mark.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Creates an instance of `HtmlDiffOutputGenerator` class. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Creates an instance of `HtmlDiffOutputGenerator` class. |

## Properties

| Name | Description |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Gets and sets the CSS-style string for Delete operation. Example: color: #003300; background-color: #ccff66; |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Gets and sets the CSS-style string for Equal operation. Example: color: #003300; background-color: #ccff66; |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Gets and sets the CSS-style string for Insert operation. Example: color: #003300; background-color: #ccff66; |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Get or set text-decoration: line-through style for the delete operation. Default value is `False`. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;DiffOperation&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;List&lt;DiffOperation&gt;&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

