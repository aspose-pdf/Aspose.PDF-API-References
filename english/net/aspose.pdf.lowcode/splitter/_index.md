---
title: "Splitter Class"
linktitle: "Splitter"
articleTitle: "Splitter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Splitter class. Represents Splitter plugin."
type: docs
weight: 870
url: "/net/aspose.pdf.lowcode/splitter/"
keywords: "Splitter, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Splitter class

Represents [`Splitter`](../../aspose.pdf.lowcode/splitter/) plugin.

```csharp
public class Splitter : IPlugin
```

## Examples

The example demonstrates how to split PDF document.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

## Constructors

| Name | Description |
| --- | --- |
| [Splitter](./splitter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](./process/)(IPluginOptions) | Starts the [`Splitter`](../../aspose.pdf.lowcode/splitter/) processing with the specified parameters. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

