---
title: "Classe ImageExtractor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.ImageExtractor. Rappresenta il plugin ImageExtractor"
type: docs
weight: 9020
url: /it/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

Rappresenta il plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementazione di IDisposable. In realtà, non è necessaria per PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Avvia l'elaborazione di PdfExtractor con i parametri specificati. |

## Osservazioni

L'oggetto `ImageExtractor` è usato per estrarre testo nei documenti PDF.

## Esempi

L'esempio dimostra come estrarre immagini da un documento PDF.

```csharp
// crea un oggetto ImageExtractor per estrarre immagini
using (ImageExtractor extractor = new ImageExtractor())
{
    // crea ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // aggiungi il percorso del file di input alle fonti dati
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // esegui il processo di estrazione
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // ottieni l'immagine dall'oggetto ResultContainer
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Vedi anche

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


