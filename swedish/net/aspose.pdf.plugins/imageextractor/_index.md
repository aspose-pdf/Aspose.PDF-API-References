---
title: "Klass ImageExtractor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.ImageExtractor-klass. Representerar ImageExtractor-plugin."
type: docs
weight: 9020
url: /sv/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

Representerar ImageExtractor‑pluginet.

```csharp
public class ImageExtractor : PdfExtractor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Faktiskt är det inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor‑bearbetning med de angivna parametrarna. |

## Anmärkningar

Objektet `ImageExtractor` används för att extrahera text i PDF-dokument.

## Exempel

Exemplet visar hur man extraherar bilder från PDF Document.

```csharp
// skapa ImageExtractor-objekt för att extrahera bilder
using (ImageExtractor extractor = new ImageExtractor())
{
    // skapa ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // lägg till inmatningsfilens sökväg till datakällorna
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // utför extraktionsprocessen
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // hämta bilden från ResultContainer-objektet
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Se även

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


