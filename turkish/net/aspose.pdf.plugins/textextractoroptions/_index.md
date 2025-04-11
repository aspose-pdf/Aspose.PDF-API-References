---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions sınıfı. TextExtractor eklentisi için metin çıkarım seçeneklerini temsil eder.
type: docs
weight: 9390
url: /tr/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions sınıfı

TextExtractor eklentisi için metin çıkarım seçeneklerini temsil eder.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | 'Raw' (varsayılan) metin biçimlendirme modu ile `TextExtractorOptions` nesnesinin yeni bir örneğini başlatır. |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Belirtilen metin biçimlendirme modu için `TextExtractorOptions` nesnesinin yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Biçimlendirme modunu alır. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor eklentisi veri koleksiyonunu döndürür. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | İşlemin adını döndürür. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Bir PDF belgesini metne dönüştürürken kullanılabilecek farklı modları tanımlar. `TextExtractorOptions` sınıfına bakın. |

## Açıklamalar

`TextExtractorOptions` nesnesi, metin çıkarım işlemi için [`TextFormattingMode`](../textextractoroptions.textformattingmode/) ve diğer seçenekleri ayarlamak için kullanılır. Ayrıca, giriş PDF belgelerini temsil eden veri (dosyalar, akışlar) eklemek için işlevler miras alır.

## Örnekler

Örnek, PDF belgesinin metin içeriğini nasıl çıkaracağınızı gösterir.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Ayrıca Bakınız

* sınıf [PdfExtractorOptions](../pdfextractoroptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)