---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor sınıfı. ImageExtractor eklentisini temsil eder
type: docs
weight: 8890
url: /tr/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor sınıfı

ImageExtractor eklentisini temsil eder.

```csharp
public class ImageExtractor : PdfExtractor
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable uygulaması. Aslında, PdfExtractor için gerekli değildir. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Belirtilen parametrelerle PdfExtractor işlemini başlatır. |

## Açıklamalar

`ImageExtractor` nesnesi, PDF belgelerindeki metni çıkarmak için kullanılır.

## Örnekler

Örnek, PDF belgesinden resimlerin nasıl çıkarılacağını gösterir.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../pdfextractor/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)