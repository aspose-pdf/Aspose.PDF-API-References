---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Optimizer. Representa o plugin Otimizador
type: docs
weight: 8970
url: /pt/net/aspose.pdf.plugins/optimizer/
---
## Classe Otimizador

Representa o plugin `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Optimizer](optimizer/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Inicia o processamento do `Optimizer` com os parâmetros especificados. |

## Exemplos

O exemplo demonstra como otimizar um documento PDF.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### Veja Também

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)