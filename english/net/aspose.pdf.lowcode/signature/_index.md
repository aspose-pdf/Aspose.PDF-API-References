---
title: "Signature Class"
linktitle: "Signature"
articleTitle: "Signature"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Signature class. Represents Signature plugin."
type: docs
weight: 850
url: "/net/aspose.pdf.lowcode/signature/"
keywords: "Signature, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Signature class

Represents [`Signature`](../../aspose.pdf.lowcode/signature/) plugin.

```csharp
public sealed class Signature : IPlugin
```

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

## Constructors

| Name | Description |
| --- | --- |
| [Signature](./signature/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Process](./process/)(IPluginOptions) | Starts the [`Signature`](../../aspose.pdf.lowcode/signature/) processing with the specified parameters. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

