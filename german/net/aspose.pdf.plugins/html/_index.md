---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Html-Klasse. Stellt das Html-Plugin dar
type: docs
weight: 8820
url: /de/net/aspose.pdf.plugins/html/
---
## Html-Klasse

Stellt das `Html`-Plugin dar.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Html](html/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementierung von IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Startet die `Html`-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF in ein HTML-Dokument konvertiert.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Das Beispiel zeigt, wie man ein HTML in ein PDF-Dokument konvertiert.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)