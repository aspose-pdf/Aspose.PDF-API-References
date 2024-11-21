---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.OutputGenerator.HtmlDiffOutputGenerator class. Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark
type: docs
weight: 1980
url: /net/aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark.

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
| [DeleteStyle](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/deletestyle/) { get; set; } | Gets and sets the CSS-style string for Delete operation. Example: |
| [EqualStyle](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/equalstyle/) { get; set; } | Gets and sets the CSS-style string for Equal operation. Example: |
| [InsertStyle](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/insertstyle/) { get; set; } | Gets and sets the CSS-style string for Insert operation. Example: |
| [StrikethroughDeleted](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Get or set text-decoration: line-through style for the delete operation. Default value is `False`. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison.OutputGenerator](../../aspose.pdf.comparison.outputgenerator/)
* assembly [Aspose.PDF](../../)


