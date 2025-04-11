---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractor. Rappresenta il plugin TextExtractor
type: docs
weight: 9380
url: /it/net/aspose.pdf.plugins/textextractor/
---
## Classe TextExtractor

Rappresenta il plugin TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextExtractor](textextractor/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessario per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto `TextExtractor` viene utilizzato per estrarre testo nei documenti PDF.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

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

### Vedi Anche

* classe [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)