---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptzioniDiConversioneDelFormatoPdf.PuaProcessingStrategy. Alcuni documenti PDF contengono simboli Unicode speciali appartenenti all'Area di Utilizzo Privata PUA. Vedi la descrizione all'indirizzo https//en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli possono causare errori di conformità PDF/A, come 'Il testo viene mappato all'Area di Utilizzo Privata Unicode, ma nessun'entrata ActualText è presente.' Questa enumerazione dichiara le strategie che possono essere utilizzate per gestire i simboli PUA.
type: docs
weight: 8390
url: /it/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Enumerazione PdfFormatConversionOptions.PuaProcessingStrategy

Alcuni documenti PDF contengono simboli unicode speciali, che appartengono all'Area di Uso Privato (PUA), vedere descrizione su https://en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli causano errori di conformità PDF/A come "Il testo è mappato all'Area di Uso Privato Unicode ma non è presente alcuna voce ActualText". Questa enumerazione dichiara delle strategie che possono essere utilizzate per gestire i simboli PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Disabilita l'elaborazione dei simboli PUA. Questa strategia è utilizzata per impostazione predefinita per i documenti PDF/A con conformità di livello B. |
| SurroundPuaTextWithEmptyActualText | `1` | Inserisce un blocco di contenuto contrassegnato con una voce ActualText che contiene testo vuoto. Questa strategia dà buoni risultati per documenti senza blocchi di contenuto contrassegnati. Utilizzata per impostazione predefinita per i documenti PDF/A con conformità di livello A. |
| SubstitutePuaSymbols | `2` | Questa strategia funziona più lentamente di 'SurroundPuaTextWithEmptyActualText' ma può rimuovere gli errori di conformità PUA per documenti che non possono essere gestiti correttamente da SurroundPuaTextWithEmptyActualText. I simboli PUA vengono sostituiti con il simbolo 'spazio' o unicode speciale (alcuni simboli PUA hanno analoghi unicode). La sostituzione viene applicata non al testo del documento ma ai dati interni del font ToUnicode, quindi non influisce sulla visione del simbolo ma influisce sulla presentazione del simbolo nel sistema di buffer delle operazioni di copia/incolla. |

### Vedi Anche

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)