---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter sınıfı. XlsConverter eklentisini temsil eder
type: docs
weight: 9450
url: /tr/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter sınıfı

`XlsConverter` eklentisini temsil eder.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable uygulaması. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Belirtilen parametrelerle PdfToExcel işlemini başlatır. |

## Örnekler

Örnek, PDF'yi XLSX belgesine nasıl dönüştüreceğinizi gösterir.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)