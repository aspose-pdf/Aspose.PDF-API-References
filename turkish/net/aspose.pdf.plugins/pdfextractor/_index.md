---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor sınıfı. PDF belgelerinin sayfalarında meydana gelebilecek metin, resim ve diğer içerik türlerini çıkarmak için temel işlevselliği temsil eder.
type: docs
weight: 9060
url: /tr/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor Sınıfı

PDF belgelerinin sayfalarında meydana gelebilecek metin, resim ve diğer içerik türlerini çıkarmak için temel işlevselliği temsil eder.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable uygulaması. Aslında, PdfExtractor için gerekli değildir. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Belirtilen parametrelerle PdfExtractor işlemini başlatır. |

## Açıklamalar

[`TextExtractor`](../textextractor/) nesnesi metin çıkarmak için, veya [`ImageExtractor`](../imageextractor/) resim çıkarmak için kullanılır.

## Örnekler

Örnek, PDF belgesinin metin içeriğini nasıl çıkaracağınızı gösterir.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)