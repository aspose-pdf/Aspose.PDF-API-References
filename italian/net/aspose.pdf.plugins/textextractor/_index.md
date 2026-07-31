---
title: "Classe TextExtractor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.TextExtractor. Rappresenta il plugin TextExtractor"
type: docs
weight: 9530
url: /it/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessaria per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto `TextExtractor` è usato per estrarre testo nei documenti PDF.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

```csharp
// crea l'oggetto TextExtractor per estrarre testo nei contenuti PDF
using (TextExtractor extractor = new TextExtractor())
{
    // crea TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // aggiungi il percorso del file di input alle fonti dati
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // esegui il processo di estrazione
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // ottieni il testo estratto dall'oggetto ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Vedi anche

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


