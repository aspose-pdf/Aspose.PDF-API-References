---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer sınıfı. Optimizatör eklentisini temsil eder
type: docs
weight: 8970
url: /tr/net/aspose.pdf.plugins/optimizer/
---
## Optimizatör sınıfı

`Optimizer` eklentisini temsil eder.

```csharp
public sealed class Optimizer : IPlugin
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Optimizer](optimizer/)() | Varsayılan yapıcı. |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Belirtilen parametrelerle `Optimizer` işlemini başlatır. |

## Örnekler

Örnek, PDF belgesini nasıl optimize edeceğinizi gösterir.

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)