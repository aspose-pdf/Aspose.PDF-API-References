---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Birleştirici sınıfı. Birleştirici eklentisini temsil eder
type: docs
weight: 8940
url: /tr/net/aspose.pdf.plugins/merger/
---
## Birleştirici sınıfı

`Birleştirici` eklentisini temsil eder.

```csharp
public sealed class Merger : IPlugin
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Birleştirici](birleştirici/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [İşlem](../../aspose.pdf.plugins/birleştirici/i̇şlem/)(IPluginOptions) | Belirtilen parametrelerle `Birleştirici` işlemini başlatır. |

## Örnekler

Örnek, iki PDF belgesini nasıl birleştireceğini gösterir.

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)