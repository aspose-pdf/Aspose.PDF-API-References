---
title: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF per .NET API Reference
description: A proprietà di questo tipo È possibile assegnare un delegato creato dal metodo personalizzato che implementa lelaborazione del salvataggio esterno dellimmagine che è stata estratta da SVG creata da PDF e deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso elaborazione come il salvataggio auto-creato in stream o su disco può essere eseguito in quel codice personalizzato e quel codice personalizzato deve restituire il percorso o qualsiasi altra stringa senza virgolette che verrà successivamente incorporato nellSVG generato invece del presunto percorso originale per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dellimmagine devono essere eseguite nel codice del metodo fornito poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se lelaborazione di questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso non nel codice personalizzato impostare nel codice personalizzato il flag CustomProcessingCancelled della variabile del parametro imageSavingInfo Segnala al convertitore che tutti i passaggi necessari per lelaborazione di quella risorsa deve essere eseguita nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno . rappresenta le informazioni sullimmagine salvata che possono essere utilizzate nel codice personalizzatodeve restituire una stringa che rappresenta lURL dellimmagine che verrà inserita in SVG
type: docs
weight: 6460
url: /it/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

A proprietà di questo tipo È possibile assegnare un delegato creato dal metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine che è stata estratta da SVG creata da PDF e deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso elaborazione (come il salvataggio auto-creato in stream o su disco) può essere eseguito in quel codice personalizzato e quel codice personalizzato deve restituire il percorso (o qualsiasi altra stringa senza virgolette) che verrà successivamente incorporato nell'SVG generato invece del presunto percorso originale per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione di questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo' Segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa deve essere eseguita nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno . rappresenta le informazioni sull'immagine salvata che possono essere utilizzate nel codice personalizzatodeve restituire una stringa che rappresenta l'URL dell'immagine che verrà inserita in SVG

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Guarda anche

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo)
* class [SvgSaveOptions](../svgsaveoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->