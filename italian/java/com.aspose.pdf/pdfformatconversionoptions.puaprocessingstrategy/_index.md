---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Alcuni documenti PDF contengono simboli Unicode speciali, appartenenti all'Area di Uso Privato (PUA); vedere la descrizione su https://en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli."
type: docs
weight: 3750
url: /it/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Alcuni documenti PDF contengono simboli Unicode speciali, appartenenti all'Area di Uso Privato (PUA); vedere la descrizione su https://en.wikipedia.org/wiki/Private_Use_Areas. Questi simboli causano errori di conformità PDF/A come "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Questa enumerazione dichiara le strategie che possono essere usate per gestire i simboli PUA.

## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Disabilita l'elaborazione dei simboli PUA. Questa strategia è usata per impostazione predefinita nei documenti PDF/A con conformità di livello B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Questa strategia funziona più lentamente rispetto a 'SurroundPuaTextWithEmptyActualText' ma può rimuovere gli errori conformi a PUA per i documenti che non possono essere gestiti correttamente da SurroundPuaTextWithEmptyActualText. I simboli PUA sono sostituiti con il simbolo 'space' o con Unicode speciale (alcuni simboli PUA hanno analoghi Unicode). La sostituzione viene applicata non al testo del documento ma ai dati interni del font ToUnicode, quindi non influisce sulla visualizzazione del simbolo ma influisce sulla sua presentazione nell'operazione di copia/incolla del buffer di sistema. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Inserisce un blocco di contenuto contrassegnato con voce ActualText che contiene testo vuoto. Questa strategia fornisce buoni risultati per i documenti senza blocchi di contenuto contrassegnati. È usata per impostazione predefinita nei documenti PDF/A con conformità di livello A. |

### None {#None}
```
public static final int None
```

Disabilita l'elaborazione dei simboli PUA. Questa strategia è usata per impostazione predefinita nei documenti PDF/A con conformità di livello B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Questa strategia funziona più lentamente rispetto a 'SurroundPuaTextWithEmptyActualText' ma può rimuovere gli errori conformi a PUA per i documenti che non possono essere gestiti correttamente da SurroundPuaTextWithEmptyActualText. I simboli PUA sono sostituiti con il simbolo 'space' o con Unicode speciale (alcuni simboli PUA hanno analoghi Unicode). La sostituzione viene applicata non al testo del documento ma ai dati interni del font ToUnicode, quindi non influisce sulla visualizzazione del simbolo ma influisce sulla sua presentazione nell'operazione di copia/incolla del buffer di sistema.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Inserisce un blocco di contenuto contrassegnato con voce ActualText che contiene testo vuoto. Questa strategia fornisce buoni risultati per i documenti senza blocchi di contenuto contrassegnati. È usata per impostazione predefinita nei documenti PDF/A con conformità di livello A.
