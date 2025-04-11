---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Splitter. Representa o plugin Splitter
type: docs
weight: 9280
url: /pt/net/aspose.pdf.plugins/splitter/
---
## Classe Splitter

Representa o plugin `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Splitter](splitter/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Inicia o processamento do `Splitter` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como dividir um documento PDF.

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

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)