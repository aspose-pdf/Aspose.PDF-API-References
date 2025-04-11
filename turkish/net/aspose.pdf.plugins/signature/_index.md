---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature sınıfı. İmza eklentisini temsil eder
type: docs
weight: 9260
url: /tr/net/aspose.pdf.plugins/signature/
---
## İmza sınıfı

`Signature` eklentisini temsil eder.

```csharp
public sealed class Signature : IPlugin
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Signature](signature/)() | Varsayılan yapıcı. |

## Metodlar

| Ad | Açıklama |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Belirtilen parametrelerle `Signature` işlemini başlatır. |

## Örnekler

Örnek, PDF belgesini nasıl imzalayacağınızı gösterir.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)