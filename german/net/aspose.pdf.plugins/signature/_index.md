---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature-Klasse. Stellt das Signature-Plugin dar
type: docs
weight: 9260
url: /de/net/aspose.pdf.plugins/signature/
---
## Signature-Klasse

Stellt das `Signature`-Plugin dar.

```csharp
public sealed class Signature : IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Signature](signature/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Startet die `Signature`-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF-Dokument signiert.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)