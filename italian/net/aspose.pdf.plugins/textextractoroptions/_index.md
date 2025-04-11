---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractorOptions. Rappresenta le opzioni di estrazione del testo per il plugin TextExtractor
type: docs
weight: 9390
url: /it/net/aspose.pdf.plugins/textextractoroptions/
---
## Classe TextExtractorOptions

Rappresenta le opzioni di estrazione del testo per il plugin TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Inizializza una nuova istanza dell'oggetto `TextExtractorOptions` con la modalità di formattazione del testo 'Raw' (predefinita). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Inizializza una nuova istanza dell'oggetto `TextExtractorOptions` per la modalità di formattazione del testo specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Ottiene la modalità di formattazione. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Restituisce il nome dell'operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfExtractor. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Definisce diverse modalità che possono essere utilizzate durante la conversione di un documento PDF in testo. Vedi la classe `TextExtractorOptions`. |

## Osservazioni

L'oggetto `TextExtractorOptions` viene utilizzato per impostare [`TextFormattingMode`](../textextractoroptions.textformattingmode/) e altre opzioni per l'operazione di estrazione del testo. Inoltre, eredita funzioni per aggiungere dati (file, flussi) che rappresentano documenti PDF di input.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Vedi Anche

* classe [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)