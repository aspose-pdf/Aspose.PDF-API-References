---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Alla proprietà di questo tipo è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG creato da PDF."
type: docs
weight: 4730
url: /it/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Alla proprietà di questo tipo è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG generato da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (ad esempio il salvataggio personalizzato su stream o su disco) può essere eseguita in quel codice personalizzato e quel codice deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
