---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Plugins.Html. Representa el plugin Html
type: docs
weight: 8820
url: /es/net/aspose.pdf.plugins/html/
---
## Clase Html

Representa el plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Html](html/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementación de IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Inicia el procesamiento de `Html` con los parámetros especificados. |

## Ejemplos

El ejemplo demuestra cómo convertir un PDF a un documento HTML.

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

El ejemplo demuestra cómo convertir un HTML a un documento PDF.

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

### Véase También

* interfaz [IPlugin](../iplugin/)
* espacio de nombres [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* ensamblado [Aspose.PDF](../../)