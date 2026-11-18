---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.Optimizer class. Represents Optimizer plugin
type: docs
weight: 7610
url: /net/aspose.pdf.lowcode/optimizer/
---
## Optimizer class

Represents `Optimizer` plugin.

```csharp
public sealed class Optimizer : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [Optimizer](optimizer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/optimizer/process/)(IPluginOptions) | Starts the `Optimizer` processing with the specified parameters. |

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

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


