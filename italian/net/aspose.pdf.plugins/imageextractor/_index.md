---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.ImageExtractor. Rappresenta il plugin ImageExtractor
type: docs
weight: 8890
url: /it/net/aspose.pdf.plugins/imageextractor/
---
## Classe ImageExtractor

Rappresenta il plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessario per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto `ImageExtractor` viene utilizzato per estrarre testo nei documenti PDF.

## Esempi

L'esempio dimostra come estrarre immagini da un documento PDF.

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

### Vedi Anche

* classe [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)