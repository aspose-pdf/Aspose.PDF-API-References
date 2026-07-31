---
title: "Enum PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Alcuni documenti PDF contengono simboli Unicode speciali appartenenti all'Area di Uso Privato (PUA); vedere la descrizione su https//en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli causano errori di conformità PDF/A, come \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Questa enumerazione dichiara delle strategie che possono essere usate per gestire i simboli PUA"
type: docs
weight: 8530
url: /it/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Alcuni documenti PDF contengono simboli Unicode speciali, appartenenti all'Area di Uso Privato (PUA); vedere la descrizione su https://en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli causano errori di conformità PDF/A, come "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Questa enumerazione dichiara delle strategie che possono essere usate per gestire i simboli PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Disabilita l'elaborazione dei simboli PUA. Questa strategia è usata per impostazione predefinita nei documenti PDF/A con conformità di livello B. |
| SurroundPuaTextWithEmptyActualText | `1` | Inserisce un blocco di contenuto marcato con voce ActualText che contiene testo vuoto. Questa strategia fornisce buoni risultati per i documenti senza blocchi di contenuto marcati. È usata per impostazione predefinita nei documenti PDF/A con conformità di livello A. |
| SubstitutePuaSymbols | `2` | Questa strategia è più lenta di 'SurroundPuaTextWithEmptyActualText' ma può rimuovere gli errori di conformità PUA per i documenti che non possono essere gestiti correttamente da SurroundPuaTextWithEmptyActualText. I simboli PUA vengono sostituiti con il simbolo 'spazio' o con Unicode speciale (alcuni simboli PUA hanno analoghi Unicode). La sostituzione viene applicata non al testo del documento ma ai dati interni del carattere ToUnicode, quindi non influisce sulla visualizzazione del simbolo ma ne altera la presentazione nelle operazioni di copia/incolla del buffer di sistema. |

### Vedi anche

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


