---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.ImageExtractor. Representa o plugin ImageExtractor
type: docs
weight: 8890
url: /pt/net/aspose.pdf.plugins/imageextractor/
---
## Classe ImageExtractor

Representa o plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ImageExtractor](imageextractor/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementação de IDisposable. Na verdade, não é necessário para PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Inicia o processamento do PdfExtractor com os parâmetros especificados. |

## Observações

O objeto `ImageExtractor` é usado para extrair texto em documentos PDF.

## Exemplos

O exemplo demonstra como extrair imagens de um documento PDF.

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

### Veja Também

* classe [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)