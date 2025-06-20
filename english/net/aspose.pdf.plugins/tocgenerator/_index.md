---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator class. Represents Aspose.PDF TocGenerator plugin
type: docs
weight: 9560
url: /net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Represents Aspose.PDF TocGenerator plugin.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [TocGenerator](tocgenerator/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementation of IDisposable. In fact, it is not necessary for TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Starts the PdfGenerator processing with the specified parameters. |

## Examples

The example demonstrates how to add TOC to PDF file.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


