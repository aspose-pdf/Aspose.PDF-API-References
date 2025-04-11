---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A proprietà di tale tipo puoi assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG creato da PDF e deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio personalizzato in uno stream o su disco) può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato invece del percorso originale previsto per quella risorsa immagine. In tal caso, tutte le azioni necessarie per il salvataggio dell'immagine devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno. rappresenta informazioni sull'immagine salvata che possono essere utilizzate nel codice personalizzato deve restituire una stringa che rappresenta l'URL dell'immagine che sarà inserita nello SVG.
type: docs
weight: 10240
url: /it/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## Delegato SvgSaveOptions.EmbeddedImagesSavingStrategy

A proprietà di tale tipo puoi assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG creato da PDF e deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio personalizzato in uno stream o su disco) può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato invece del percorso originale previsto per quella risorsa immagine. In tal caso, tutte le azioni necessarie per il salvataggio dell'immagine devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno. rappresenta informazioni sull'immagine salvata che possono essere utilizzate nel codice personalizzato deve restituire una stringa che rappresenta l'URL dell'immagine che sarà inserita nello SVG.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Vedi Anche

* classe [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* classe [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)