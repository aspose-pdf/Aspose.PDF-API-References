---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter klass. Representerar Splitter-plugin
type: docs
weight: 9280
url: /sv/net/aspose.pdf.plugins/splitter/
---
## Splitter klass

Representerar `Splitter` plugin.

```csharp
public class Splitter : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Splitter](splitter/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Startar `Splitter` bearbetning med angivna parametrar. |

## Exempel

Exemplet visar hur man delar en PDF-dokument.

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

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)