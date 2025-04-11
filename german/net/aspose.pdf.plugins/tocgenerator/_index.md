---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator-Klasse. Stellt das Aspose.PDF TocGenerator-Plugin dar
type: docs
weight: 9430
url: /de/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator-Klasse

Stellt das Aspose.PDF TocGenerator-Plugin dar.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementierung von IDisposable. Tatsächlich ist es für TocGenerator nicht notwendig. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Startet die PdfGenerator-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein TOC zu einer PDF-Datei hinzufügt.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)