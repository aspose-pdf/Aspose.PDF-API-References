---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator sınıfı. Aspose.PDF TocGenerator eklentisini temsil eder
type: docs
weight: 9430
url: /tr/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator sınıfı

Aspose.PDF TocGenerator eklentisini temsil eder.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable uygulaması. Aslında, TocGenerator için gerekli değildir. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Belirtilen parametrelerle PdfGenerator işlemini başlatır. |

## Örnekler

Örnek, PDF dosyasına TOC eklemeyi göstermektedir.

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)