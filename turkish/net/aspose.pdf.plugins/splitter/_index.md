---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Bölücü sınıfı. Bölücü eklentisini temsil eder
type: docs
weight: 9280
url: /tr/net/aspose.pdf.plugins/splitter/
---
## Bölücü sınıfı

`Bölücü` eklentisini temsil eder.

```csharp
public class Splitter : IPlugin
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Bölücü](splitter/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [İşlem](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Belirtilen parametrelerle `Bölücü` işlemini başlatır. |

## Örnekler

Örnek, PDF belgesinin nasıl bölüneceğini gösterir.

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)