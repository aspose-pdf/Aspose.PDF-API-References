---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor-Klasse. Stellt die grundlegende Funktionalität zum Extrahieren von Text, Bildern und anderen Arten von Inhalten dar, die auf den Seiten von PDF-Dokumenten auftreten können.
type: docs
weight: 9060
url: /de/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor-Klasse

Stellt die grundlegende Funktionalität zum Extrahieren von Text, Bildern und anderen Arten von Inhalten dar, die auf den Seiten von PDF-Dokumenten auftreten können.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementierung von IDisposable. Tatsächlich ist es für PdfExtractor nicht notwendig. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startet die PdfExtractor-Verarbeitung mit den angegebenen Parametern. |

## Bemerkungen

Das [`TextExtractor`](../textextractor/) Objekt wird verwendet, um Text zu extrahieren, oder [`ImageExtractor`](../imageextractor/), um Bilder zu extrahieren.

## Beispiele

Das Beispiel zeigt, wie man den Textinhalt eines PDF-Dokuments extrahiert.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)