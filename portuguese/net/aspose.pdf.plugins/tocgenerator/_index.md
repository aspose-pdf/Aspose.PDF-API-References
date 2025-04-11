---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TocGenerator. Representa o plugin TocGenerator do Aspose.PDF
type: docs
weight: 9430
url: /pt/net/aspose.pdf.plugins/tocgenerator/
---
## Classe TocGenerator

Representa o plugin TocGenerator do Aspose.PDF.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TocGenerator](tocgenerator/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementação de IDisposable. Na verdade, não é necessário para TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Inicia o processamento do PdfGenerator com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como adicionar TOC a um arquivo PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)