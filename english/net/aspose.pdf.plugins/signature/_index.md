---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature class. Represents Signature plugin
type: docs
weight: 9260
url: /net/aspose.pdf.plugins/signature/
---
## Signature class

Represents `Signature` plugin.

```csharp
public sealed class Signature : IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [Signature](signature/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Starts the `Signature` processing with the specified parameters. |

## Examples

The example demonstrates how to sign PDF document.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


