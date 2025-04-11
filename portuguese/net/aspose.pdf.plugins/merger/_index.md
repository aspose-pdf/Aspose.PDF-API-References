---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Merger. Representa o plugin Merger
type: docs
weight: 8940
url: /pt/net/aspose.pdf.plugins/merger/
---
## Classe Merger

Representa o plugin `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Merger](merger/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Inicia o processamento do `Merger` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como mesclar dois documentos PDF.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)