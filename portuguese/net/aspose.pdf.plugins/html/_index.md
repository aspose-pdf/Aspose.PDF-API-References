---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Html. Representa o plugin Html
type: docs
weight: 8820
url: /pt/net/aspose.pdf.plugins/html/
---
## Classe Html

Representa o plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Html](html/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementação de IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Inicia o processamento `Html` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como converter PDF para documento HTML.

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

O exemplo demonstra como converter HTML para documento PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)