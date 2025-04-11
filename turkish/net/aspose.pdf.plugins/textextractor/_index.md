---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor sınıfı. TextExtractor eklentisini temsil eder
type: docs
weight: 9380
url: /tr/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor sınıfı

TextExtractor eklentisini temsil eder.

```csharp
public class TextExtractor : PdfExtractor
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextExtractor](textextractor/)() | Varsayılan yapıcı. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable uygulaması. Aslında, PdfExtractor için gerekli değildir. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Belirtilen parametrelerle PdfExtractor işlemini başlatır. |

## Açıklamalar

`TextExtractor` nesnesi, PDF belgelerindeki metni çıkarmak için kullanılır.

## Örnekler

Örnek, PDF belgesinin metin içeriğini nasıl çıkaracağınızı gösterir.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../pdfextractor/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)