---
title: "Classe OcrDetail"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.OcrDetail classe. Rappresenta il risultato OCR per una singola pagina di un documento o di un singolo file immagine"
type: docs
weight: 860
url: /it/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Rappresenta il risultato OCR per una singola pagina di un documento o un singolo file immagine.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OcrDetail](ocrdetail/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Un messaggio di errore che descrive il motivo per cui OCR è fallito per questa pagina, se Success è false. Null altrimenti. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | Il contenuto di testo estratto dalla pagina. Null se Success è false o se non è stato trovato alcun testo. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | Il numero di pagina basato su 1 all'interno del documento sorgente. Per le immagini a pagina singola, sarà sempre 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indica se l'estrazione OCR per questa pagina specifica è avvenuta con successo. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Confronta l'istanza OcrDetail corrente con un altro oggetto OcrDetail basandosi sulla loro proprietà PageNumber. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


