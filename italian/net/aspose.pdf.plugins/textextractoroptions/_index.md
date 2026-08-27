---
title: "Classe TextExtractorOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.TextExtractorOptions. Rappresenta le opzioni di estrazione del testo per il plugin TextExtractor."
type: docs
weight: 9540
url: /it/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

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
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Restituisce la raccolta dati del plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Restituisce il nome dell'operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta dati del plugin PdfExtractor. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Definisce diverse modalità che possono essere utilizzate durante la conversione di un documento PDF in testo. Vedi la classe `TextExtractorOptions`. |

## Osservazioni

L'oggetto `TextExtractorOptions` è usato per impostare [`TextFormattingMode`](../textextractoroptions.textformattingmode/) e altre opzioni per l'operazione di estrazione del testo. Inoltre, eredita funzioni per aggiungere dati (file, stream) che rappresentano i documenti PDF di input.

## Esempi

L'esempio dimostra come estrarre il contenuto testuale di un documento PDF.

```csharp
// crea un oggetto TextExtractor per estrarre i contenuti PDF
using (TextExtractor extractor = new TextExtractor())
{
    // crea un oggetto TextExtractorOptions per impostare TextFormattingMode (Pure,  o Raw - predefinito)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // aggiungi il percorso del file di input alle fonti dati
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // esegui il processo di estrazione
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // ottieni il testo estratto dall'oggetto ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Vedi anche

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


