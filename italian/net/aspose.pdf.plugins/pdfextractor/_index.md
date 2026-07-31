---
title: "Classe PdfExtractor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Plugins.PdfExtractor classe. Rappresenta la funzionalità di base per estrarre testo, immagini e altri tipi di contenuto che possono comparire nelle pagine dei documenti PDF"
type: docs
weight: 9210
url: /it/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Rappresenta la funzionalità di base per estrarre testo, immagini e altri tipi di contenuto che possono comparire nelle pagine dei documenti PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessaria per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto [`TextExtractor`](../textextractor/) è usato per estrarre testo, oppure [`ImageExtractor`](../imageextractor/) per estrarre immagini.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

```csharp
// crea un oggetto TextExtractor per estrarre i contenuti PDF
using (TextExtractor extractor = new TextExtractor())
{
    // crea l'oggetto TextExtractorOptions per impostare le istruzioni
    textExtractorOptions = new TextExtractorOptions();
    
    // aggiungi il percorso del file di input alle fonti dati
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // esegui il processo di estrazione
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // ottieni il testo estratto dall'oggetto ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


