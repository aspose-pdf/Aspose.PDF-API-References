---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator-Klasse. Stellt das Aspose.PDF TableGenerator-Plugin dar
type: docs
weight: 9350
url: /de/net/aspose.pdf.plugins/tablegenerator/
---
## Klasse TableGenerator

Stellt das Aspose.PDF TableGenerator-Plugin dar.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementierung von IDisposable. Tatsächlich ist es für TableGenerator nicht notwendig. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Startet die PdfGenerator-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man eine Tabelle zu einer PDF-Datei hinzufügt.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)