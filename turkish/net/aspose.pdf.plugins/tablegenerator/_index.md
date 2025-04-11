---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator sınıfı. Aspose.PDF TableGenerator eklentisini temsil eder
type: docs
weight: 9350
url: /tr/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator sınıfı

Aspose.PDF TableGenerator eklentisini temsil eder.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | IDisposable uygulaması. Aslında, TableGenerator için gerekli değildir. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Belirtilen parametrelerle PdfGenerator işlemini başlatır. |

## Örnekler

Örnek, PDF dosyasına nasıl tablo ekleyeceğini gösterir.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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