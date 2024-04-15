---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter class. Represents Splitter plugin
type: docs
weight: 7120
url: /net/aspose.pdf.plugins/splitter/
---
## Splitter class

Represents `Splitter` plugin.

```csharp
public class Splitter : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [Splitter](splitter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Starts the `Splitter` processing with the specified parameters. |

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

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


