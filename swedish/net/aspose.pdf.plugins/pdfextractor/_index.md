---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor klass. Representerar grundläggande funktionalitet för att extrahera text, bilder och andra typer av innehåll som kan förekomma på sidorna av PDF-dokument
type: docs
weight: 9060
url: /sv/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor klass

Representerar grundläggande funktionalitet för att extrahera text, bilder och andra typer av innehåll som kan förekomma på sidorna av PDF-dokument.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Egentligen är det inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor-behandling med de angivna parametrarna. |

## Kommentarer

Objektet [`TextExtractor`](../textextractor/) används för att extrahera text, eller [`ImageExtractor`](../imageextractor/) för att extrahera bilder.

## Exempel

Exemplet visar hur man extraherar textinnehåll från ett PDF-dokument.

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

### Se Även

* gränssnitt [IPlugin](../iplugin/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* sammansättning [Aspose.PDF](../../)