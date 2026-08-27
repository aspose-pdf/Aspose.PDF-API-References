---
title: "Classe TextRecognitionResult"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.TextRecognitionResult. Rappresenta i risultati OCR aggregati per un singolo documento sorgente"
type: docs
weight: 1180
url: /it/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

Rappresenta i risultati OCR aggregati per un singolo documento sorgente.

```csharp
public class TextRecognitionResult
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | Un elenco contenente i risultati OCR dettagliati per ogni pagina del documento. Per file con immagine singola, questo elenco conterrà tipicamente una voce OcrDetail con PageNumber = 1. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | Indica se l'OCR è stato completato con successo per TUTTE le pagine di questo documento. False se qualche OcrDetail in OcrDetails ha Success = false. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | Identificatore per il file sorgente (ad esempio, il percorso completo o un nome univoco). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | Un messaggio di errore consolidato se OverallSuccess è false, oppure un riepilogo se qualche pagina è fallita. Null se OverallSuccess è true. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | Ottiene o imposta le statistiche totali di utilizzo per l'elaborazione di questo documento (tutte le pagine). |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


