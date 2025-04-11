---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfExtractor. Rappresenta la funzionalità di base per estrarre testo, immagini e altri tipi di contenuto che possono apparire sulle pagine dei documenti PDF
type: docs
weight: 9060
url: /it/net/aspose.pdf.plugins/pdfextractor/
---
## Classe PdfExtractor

Rappresenta la funzionalità di base per estrarre testo, immagini e altri tipi di contenuto che possono apparire sulle pagine dei documenti PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessario per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto [`TextExtractor`](../textextractor/) è utilizzato per estrarre testo, o [`ImageExtractor`](../imageextractor/) per estrarre immagini.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

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

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)