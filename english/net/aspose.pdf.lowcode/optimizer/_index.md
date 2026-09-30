---
title: "Optimizer Class"
linktitle: "Optimizer"
articleTitle: "Optimizer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Optimizer class. Represents Optimizer plugin."
type: docs
weight: 560
url: "/net/aspose.pdf.lowcode/optimizer/"
keywords: "Optimizer, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Optimizer class

Represents [`Optimizer`](../../aspose.pdf.lowcode/optimizer/) plugin.

```csharp
public sealed class Optimizer : IPlugin
```

## Examples

The example demonstrates how to optimize PDF document.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

## Constructors

| Name | Description |
| --- | --- |
| [Optimizer](./optimizer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](./process/)(IPluginOptions) | Starts the [`Optimizer`](../../aspose.pdf.lowcode/optimizer/) processing with the specified parameters. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

