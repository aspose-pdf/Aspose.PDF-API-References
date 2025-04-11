---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor klass. Representerar ImageExtractor-plugin
type: docs
weight: 8890
url: /sv/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor klass

Representerar ImageExtractor-plugin.

```csharp
public class ImageExtractor : PdfExtractor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Faktiskt, det är inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor-behandling med angivna parametrar. |

## Kommentarer

`ImageExtractor`-objektet används för att extrahera text i PDF-dokument.

## Exempel

Exemplet visar hur man extraherar bilder från PDF-dokument.

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

### Se Även

* klass [PdfExtractor](../pdfextractor/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* sammansättning [Aspose.PDF](../../)