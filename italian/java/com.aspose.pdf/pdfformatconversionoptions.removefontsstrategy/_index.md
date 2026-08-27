---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Alcuni documenti hanno una dimensione elevata dopo la conversione in formato PDF/A. Per ridurre la dimensione del file per questi documenti è necessario definire una strategia di rimozione dei font. Questa enumerazione."
type: docs
weight: 3760
url: /it/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Alcuni documenti hanno una dimensione elevata dopo la conversione in formato PDF/A. Per ridurre la dimensione del file per questi documenti è necessario definire una strategia di rimozione dei caratteri. Questa enumerazione dichiara le strategie che possono essere usate per ottimizzare l'uso dei caratteri. Ogni strategia di questa enumerazione ha senso solo quando il flag {@code OptimizeFileSize} è impostato.

## Campi

| Campo | Descrizione |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Questa strategia rimuove tutti i font che hanno duplicati nel documento. Se il documento contiene un gruppo di font duplicati, solo un font di questo gruppo viene incorporato nel documento. Tutti gli altri font di questo gruppo vengono rimossi dal documento, ogni font rimosso viene sostituito con l'analogo già incorporato. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Questa strategia è simile a {@code RemoveDuplicatedFonts} ma rimuove non i font completamente duplicati, bensì i font che sono simili tra loro e differiscono solo per il parametro "Widths". Questo parametro contiene un insieme di larghezze per i simboli specifici del font. Ogni valore di larghezza di questo insieme "Widths" non è la larghezza reale del simbolo (glifo), la larghezza reale per questo simbolo è già definita nei dati binari del font. Il valore di larghezza dell'insieme "Widths" indica la larghezza visiva per questo simbolo – la larghezza che il software di visualizzazione PDF deve impostare durante la visualizzazione del simbolo al posto della larghezza reale definita nel font. Più precisamente, la specifica indica: i visualizzatori Acrobat 5.0 e successivi usano le larghezze dei glifi memorizzate nel dizionario del font per sovrascrivere le larghezze dei glifi nel programma del font stesso, migliorando la coerenza della visualizzazione e della stampa del documento. Questa strategia è più efficace di {@code RemoveDuplicatedFonts} ma l'uso di questa strategia in alcuni casi potrebbe teoricamente danneggiare la presentazione visiva del documento convertito. Questo difetto è possibile perché le larghezze dichiarate dei font potrebbero differire per lo stesso simbolo e, in tal caso, la larghezza di questo simbolo verrà modificata con una nuova dopo la sostituzione del font – quando il font rimosso verrà sostituito nel documento con quello già incorporato. E se la larghezza visiva del simbolo verrà modificata – verrà mostrata in modo errato e questa differenza potrebbe causare difetti visivi come sovrapposizione del testo o altri problemi. Tuttavia il difetto visivo descritto è un caso molto raro e questa strategia riduce la dimensione del documento in modo più efficace. |
| [SubsetFonts](#SubsetFonts) | Questa è la strategia più efficace per ridurre le dimensioni del documento. Prende insiemi di font completamente incorporati e li riduce solo ai sottoinsiemi utilizzati. È consigliato utilizzare questa strategia in combinazione con {@code RemoveDuplicatedFonts} o {@code RemoveSimilarFontsWithDifferentWidths} per ottenere un effetto di compressione multipla sulla dimensione del file. L'uso simultaneo di tutte e tre le strategie non ha senso e la strategia {@code RemoveSimilarFontsWithDifferentWidths} non verrà utilizzata in questo caso. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Questa strategia rimuove tutti i font che hanno duplicati nel documento. Se il documento contiene un gruppo di font duplicati, solo un font di questo gruppo viene incorporato nel documento. Tutti gli altri font di questo gruppo vengono rimossi dal documento, ogni font rimosso viene sostituito con l'analogo già incorporato.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Questa strategia è simile a {@code RemoveDuplicatedFonts} ma rimuove non i font completamente duplicati, bensì i font che sono simili tra loro e differiscono solo per il parametro "Widths". Questo parametro contiene un insieme di larghezze per i simboli specifici del font. Ogni valore di larghezza di questo insieme "Widths" non è la larghezza reale del simbolo (glifo), la larghezza reale per questo simbolo è già definita nei dati binari del font. Il valore di larghezza dell'insieme "Widths" indica la larghezza visiva per questo simbolo – la larghezza che il software di visualizzazione PDF deve impostare durante la visualizzazione del simbolo al posto della larghezza reale definita nel font. Più precisamente, la specifica indica: i visualizzatori Acrobat 5.0 e successivi usano le larghezze dei glifi memorizzate nel dizionario del font per sovrascrivere le larghezze dei glifi nel programma del font stesso, migliorando la coerenza della visualizzazione e della stampa del documento. Questa strategia è più efficace di {@code RemoveDuplicatedFonts} ma l'uso di questa strategia in alcuni casi potrebbe teoricamente danneggiare la presentazione visiva del documento convertito. Questo difetto è possibile perché le larghezze dichiarate dei font potrebbero differire per lo stesso simbolo e, in tal caso, la larghezza di questo simbolo verrà modificata con una nuova dopo la sostituzione del font – quando il font rimosso verrà sostituito nel documento con quello già incorporato. E se la larghezza visiva del simbolo verrà modificata – verrà mostrata in modo errato e questa differenza potrebbe causare difetti visivi come sovrapposizione del testo o altri problemi. Tuttavia il difetto visivo descritto è un caso molto raro e questa strategia riduce la dimensione del documento in modo più efficace.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Questa è la strategia più efficace per ridurre le dimensioni del documento. Prende insiemi di font completamente incorporati e li riduce solo ai sottoinsiemi utilizzati. È consigliato utilizzare questa strategia in combinazione con {@code RemoveDuplicatedFonts} o {@code RemoveSimilarFontsWithDifferentWidths} per ottenere un effetto di compressione multipla sulla dimensione del file. L'uso simultaneo di tutte e tre le strategie non ha senso e la strategia {@code RemoveSimilarFontsWithDifferentWidths} non verrà utilizzata in questo caso.
