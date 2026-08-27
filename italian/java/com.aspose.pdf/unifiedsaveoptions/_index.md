---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe rappresenta le opzioni di salvataggio per il salvataggio che utilizza un metodo di conversione unificato (con modello interno di documento unificato)."
type: docs
weight: 5420
url: /it/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Questa classe rappresenta le opzioni di salvataggio per il salvataggio che utilizza un metodo di conversione unificato (con modello interno di documento unificato).

## Campi

| Campo | Descrizione |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Elabora le pagine in pochi thread. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Rappresenta il processore interno di eventi di avanzamento che funziona durante la conversione e traduce gli eventi di conversione delle fasi interne in eventi di avanzamento totale esterni. Inoltre, la classe trasmette eventi che consentono di liberare risorse non più necessarie. Questa classe interna gestisce gli eventi di avanzamento da PDF a APS e da APS a [Other format] per calcolare l'avanzamento totale e informare il codice del cliente su tale avanzamento totale. La classe utilizza due tipi di eventi: conversione modello ApsToExternal e eventi di conversione da PDF a APS per generare eventi di avanzamento totale. L'esportazione ha tre fasi: 1) PDF a APS 2) riconoscimento APS 3) esportazione APS nel formato di destinazione. Il costruttore consente di regolare quante pagine vengono convertite e quale sia la parte approssimativa di questa o di quell'altra fase nell'avanzamento totale. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Questo attributo attiva la funzionalità di estrazione di immagini o testo per documenti PDF con sottolivello OCR. Valore: {@code true} il testo verrà estratto nel documento risultante; altrimenti, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo identiche affiancate. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi dell'immagine (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Questo attributo attiva la funzionalità per estrarre immagini o testo dai documenti PDF con sottolivello OCR. </p>Value: {@code true} il testo verrà estratto nel documento risultante; altrimenti, {@code false}. <hr> Valore predefinito == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Rappresenta il processore interno di eventi di avanzamento che funziona durante la conversione e traduce gli eventi di conversione delle fasi interne in eventi di avanzamento totale esterni. Inoltre, la classe trasmette eventi che consentono di liberare risorse non più necessarie. Questa classe interna gestisce gli eventi di avanzamento da PDF a APS e da APS a [Other format] per calcolare l'avanzamento totale e informare il codice del cliente su tale avanzamento totale. La classe utilizza due tipi di eventi: conversione modello ApsToExternal e eventi di conversione da PDF a APS per generare eventi di avanzamento totale. L'esportazione ha tre fasi: 1) PDF a APS 2) riconoscimento APS 3) esportazione APS nel formato di destinazione. Il costruttore consente di regolare quante pagine vengono convertite e quale sia la parte approssimativa di questa o di quell'altra fase nell'avanzamento totale. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo identiche affiancate. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi dell'immagine (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Elabora le pagine in pochi thread.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Rappresenta il processore interno di eventi di avanzamento che funziona durante la conversione e traduce gli eventi di conversione delle fasi interne in eventi di avanzamento totale esterni. Inoltre, la classe trasmette eventi che consentono di liberare risorse non più necessarie. Questa classe interna gestisce gli eventi di avanzamento da PDF a APS e da APS a [Other format] per calcolare l'avanzamento totale e informare il codice del cliente su tale avanzamento totale. La classe utilizza due tipi di eventi: conversione modello ApsToExternal e eventi di conversione da PDF a APS per generare eventi di avanzamento totale. L'esportazione ha tre fasi: 1) PDF a APS 2) riconoscimento APS 3) esportazione APS nel formato di destinazione. Il costruttore consente di regolare quante pagine vengono convertite e quale sia la parte approssimativa di questa o di quell'altra fase nell'avanzamento totale.

**Returns:**
Istanza di ConversionProgressEventsTranslator

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Questo attributo attiva la funzionalità di estrazione di immagini o testo per documenti PDF con sottolivello OCR. Valore: {@code true} il testo verrà estratto nel documento risultante; altrimenti, {@code false}.

**Returns:**
valore booleano

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo identiche affiancate. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi dell'immagine (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria.

**Returns:**
valore booleano

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Questo attributo attiva la funzionalità per estrarre immagini o testo dai documenti PDF con sottolivello OCR. </p>Value: {@code true} il testo verrà estratto nel documento risultante; altrimenti, {@code false}. <hr> Valore predefinito == false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Rappresenta il processore interno di eventi di avanzamento che funziona durante la conversione e traduce gli eventi di conversione delle fasi interne in eventi di avanzamento totale esterni. Inoltre, la classe trasmette eventi che consentono di liberare risorse non più necessarie. Questa classe interna gestisce gli eventi di avanzamento da PDF a APS e da APS a [Other format] per calcolare l'avanzamento totale e informare il codice del cliente su tale avanzamento totale. La classe utilizza due tipi di eventi: conversione modello ApsToExternal e eventi di conversione da PDF a APS per generare eventi di avanzamento totale. L'esportazione ha tre fasi: 1) PDF a APS 2) riconoscimento APS 3) esportazione APS nel formato di destinazione. Il costruttore consente di regolare quante pagine vengono convertite e quale sia la parte approssimativa di questa o di quell'altra fase nell'avanzamento totale.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo identiche affiancate. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi dell'immagine (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valore booleano |
