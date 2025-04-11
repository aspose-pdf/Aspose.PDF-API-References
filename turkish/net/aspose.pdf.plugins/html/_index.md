---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Html sınıfı. Html eklentisini temsil eder
type: docs
weight: 8820
url: /tr/net/aspose.pdf.plugins/html/
---
## Html Sınıfı

`Html` eklentisini temsil eder.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Html](html/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | IDisposable uygulaması. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Belirtilen parametrelerle `Html` işleme başlatır. |

## Örnekler

Örnek, PDF'yi HTML belgesine dönüştürmenin nasıl yapılacağını gösterir.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

Örnek, HTML'yi PDF belgesine dönüştürmenin nasıl yapılacağını gösterir.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
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