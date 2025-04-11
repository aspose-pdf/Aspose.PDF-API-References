---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor klass. Representerar TextExtractor-plugin
type: docs
weight: 9380
url: /sv/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor klass

Representerar TextExtractor-plugin.

```csharp
public class TextExtractor : PdfExtractor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextExtractor](textextractor/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Faktiskt, det är inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor-behandling med angivna parametrar. |

## Kommentarer

`TextExtractor`-objektet används för att extrahera text i PDF-dokument.

## Exempel

Exemplet visar hur man extraherar textinnehållet i ett PDF-dokument.

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

### Se Även

* klass [PdfExtractor](../pdfextractor/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)