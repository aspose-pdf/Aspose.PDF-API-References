---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Merger class. Represents Merger plugin
type: docs
weight: 8940
url: /net/aspose.pdf.plugins/merger/
---
## Merger class

Represents `Merger` plugin.

```csharp
public sealed class Merger : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [Merger](merger/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Starts the `Merger` processing with the specified parameters. |

## Examples

The example demonstrates how to merge two PDF documents.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


