---
title: "Klass Html"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Html-klass. Representerar Html‑plugin."
type: docs
weight: 8950
url: /sv/net/aspose.pdf.plugins/html/
---
## Html class

Representerar `Html`‑plugin.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Html](html/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementering av IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Startar `Html`‑behandlingen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man konverterar PDF till ett HTML‑dokument.

```csharp
// skapa Html
var converter = new Html();
// skapa PdfToHtmlOptions‑objekt för att ange utdataformat som fil med inbäddade resurser
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Exemplet visar hur man konverterar HTML till ett PDF‑dokument.

```csharp
// skapa Html
var converter = new Html();
// skapa HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


