---
title: "MarkdownDiffOutputGenerator Class"
linktitle: "MarkdownDiffOutputGenerator"
articleTitle: "MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF for .NET"
description: "Represents a class for generating markdown representation of texts differences. Because of the markdown syntax, it is not possible to show changes to whitesp..."
type: docs
weight: 140
url: "/net/aspose.pdf.comparison/markdowndiffoutputgenerator/"
keywords: "MarkdownDiffOutputGenerator, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MarkdownDiffOutputGenerator class

Represents a class for generating markdown representation of texts differences.
 Because of the markdown syntax, it is not possible to show changes to whitespace characters.
 Selection of changes makes adding whitespace characters around formatting,
 otherwise markdown viewer will not correctly display the text.
 Deleted line breaks are indicated by - paragraph mark.

```csharp
public class MarkdownDiffOutputGenerator : IStringOutputGenerator, IFileOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownDiffOutputGenerator](./markdowndiffoutputgenerator/#constructor) | Initializes a new instance of the MarkdownDiffOutputGenerator class. |

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

