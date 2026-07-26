---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi. Usa la modalità RecognitionMode.Textbox quando il documento risultante non sarà pesantemente."
type: docs
weight: 1050
url: /it/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi. Utilizzare la modalità **RecognitionMode.Textbox** quando il documento risultante non sarà modificato intensamente. Le caselle di testo sono facili da modificare quando non c'è molto da fare. Utilizzare la modalità **RecognitionMode.Flow** quando il documento di output necessita di ulteriori modifiche. I paragrafi e le linee di testo nella modalità flow consentono una facile modifica del testo, ma gli oggetti di formattazione non supportati appariranno peggio rispetto alla modalità **RecognitionMode.Textbox**.

## Campi

| Campo | Descrizione |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Una modalità Flow alternativa che supporta il riconoscimento delle tabelle. |
| [Flow](#Flow) | Modalità di riconoscimento completa, il motore esegue il raggruppamento e l'analisi multilivello per ripristinare l'intento originale dell'autore del documento e produrre un documento il più modificabile possibile. |
| [Textbox](#Textbox) | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale del file PDF, ma la modificabilità del documento risultante potrebbe essere limitata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Una modalità Flow alternativa che supporta il riconoscimento delle tabelle.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Modalità di riconoscimento completa, il motore esegue il raggruppamento e l'analisi multilivello per ripristinare l'intento originale dell'autore del documento e produrre un documento il più modificabile possibile.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Questa modalità è veloce e buona per preservare al massimo l'aspetto originale del file PDF, ma la modificabilità del documento risultante potrebbe essere limitata.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
