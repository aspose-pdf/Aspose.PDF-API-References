---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "A questa proprietà puoi assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di risorse esterne (Font o Immagine) estratte dal PDF e che devono essere salvate."
type: docs
weight: 2150
url: /it/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Per questa proprietà è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di una risorsa esterna (Font o Immagine) estratta dal PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire il percorso (o qualsiasi altra stringa senza virgolette) che verrà successivamente incorporato nell'HTML generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'resourceSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Metodo invocato |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Metodo invocato
