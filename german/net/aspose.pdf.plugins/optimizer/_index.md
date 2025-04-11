---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer-Klasse. Stellt das Optimizer-Plugin dar
type: docs
weight: 8970
url: /de/net/aspose.pdf.plugins/optimizer/
---
## Optimizer-Klasse

Stellt das `Optimizer`-Plugin dar.

```csharp
public sealed class Optimizer : IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Optimizer](optimizer/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Startet die `Optimizer`-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF-Dokument optimiert.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)