---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor-Klasse. Stellt das ImageExtractor-Plugin dar
type: docs
weight: 8890
url: /de/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor-Klasse

Stellt das ImageExtractor-Plugin dar.

```csharp
public class ImageExtractor : PdfExtractor
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementierung von IDisposable. Tatsächlich ist es für PdfExtractor nicht notwendig. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startet die PdfExtractor-Verarbeitung mit den angegebenen Parametern. |

## Bemerkungen

Das `ImageExtractor`-Objekt wird verwendet, um Text in PDF-Dokumenten zu extrahieren.

## Beispiele

Das Beispiel zeigt, wie man Bilder aus einem PDF-Dokument extrahiert.

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

### Siehe auch

* Klasse [PdfExtractor](../pdfextractor/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)