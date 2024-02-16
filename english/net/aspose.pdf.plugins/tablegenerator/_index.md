---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator class. Represents Aspose.PDF TableGenerator plugin
type: docs
weight: 7100
url: /net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Represents Aspose.PDF TableGenerator plugin.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [TableGenerator](tablegenerator/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementation of IDisposable. In fact, it is not necessary for TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Starts the PdfGenerator processing with the specified parameters. |

## Examples

The example demonstrates how to add table to PDF file.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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


