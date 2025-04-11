---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor-Klasse. Stellt das TextExtractor-Plugin dar
type: docs
weight: 9380
url: /de/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor-Klasse

Stellt das TextExtractor-Plugin dar.

```csharp
public class TextExtractor : PdfExtractor
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextExtractor](textextractor/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementierung von IDisposable. Tatsächlich ist es für PdfExtractor nicht notwendig. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startet die PdfExtractor-Verarbeitung mit den angegebenen Parametern. |

## Bemerkungen

Das `TextExtractor`-Objekt wird verwendet, um Text in PDF-Dokumenten zu extrahieren.

## Beispiele

Das Beispiel zeigt, wie man den Textinhalt eines PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [PdfExtractor](../pdfextractor/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)