---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.OutputGenerator.MarkdownDiffOutputGenerator class. Represents a class for generating markdown representation of texts differences. Because of the markdown syntax it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by  paragraph mark
type: docs
weight: 1800
url: /net/aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

Represents a class for generating markdown representation of texts differences. Because of the markdown syntax, it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting, otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by - paragraph mark.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](../../aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Generates the output based on the differences between texts and saves it to a file. |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison.OutputGenerator](../../aspose.pdf.comparison.outputgenerator/)
* assembly [Aspose.PDF](../../)


