---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Quando il file PDF (che di solito ha un layout fisso) viene convertito, il motore di conversione tenta di eseguire il raggruppamento e l'analisi a più livelli per ripristinare il documento originale."
type: docs
weight: 1250
url: /it/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Quando un file PDF (che di solito ha un layout fisso) viene convertito, il motore di conversione tenta di eseguire raggruppamenti e analisi a più livelli per ripristinare l'intento originale dell'autore del documento e produrre un risultato in layout fluido. Questa proprietà regola tale conversione per il metodo desiderato di riconoscimento del contenuto.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Fixed](#Fixed) | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale delle pagine, ma sfortunatamente molti lettori EPUB non supportano xhtml con layout fisso |
| [Flow](#Flow) | Modalità di riconoscimento completo, il motore tenta di eseguire il raggruppamento e l'analisi a più livelli per ripristinare l'intento originale dell'autore del documento e produrre xhtml con layout fluido. |
| [PdfFlow](#PdfFlow) | L'idea principale di questa conversione si basa sul salvare l'ordine "naturale" di rendering del contenuto che si forma durante l'elaborazione dei documenti pdf. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Questa modalità è veloce e buona per preservare al massimo l'aspetto originale delle pagine, ma sfortunatamente molti lettori EPUB non supportano xhtml con layout fisso

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Modalità di riconoscimento completo, il motore tenta di eseguire il raggruppamento e l'analisi a più livelli per ripristinare l'intento originale dell'autore del documento e produrre xhtml con layout fluido.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

L'idea principale di questa conversione si basa sul salvare l'ordine "naturale" di rendering del contenuto che si forma durante l'elaborazione dei documenti pdf.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
