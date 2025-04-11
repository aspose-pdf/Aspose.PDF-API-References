---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter-Klasse. Stellt das Splitter-Plugin dar
type: docs
weight: 9280
url: /de/net/aspose.pdf.plugins/splitter/
---
## Splitter-Klasse

Stellt das `Splitter`-Plugin dar.

```csharp
public class Splitter : IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Splitter](splitter/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Startet die `Splitter`-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF-Dokument aufteilt.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)