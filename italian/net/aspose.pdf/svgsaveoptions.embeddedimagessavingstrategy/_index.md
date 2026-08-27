---
title: "Delegato SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Alla proprietà di questo tipo è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG generato da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione, ad esempio il salvataggio personalizzato su stream o su disco, può essere eseguita nel codice personalizzato e tale codice deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non verrà utilizzato. Se, per qualche motivo, l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso e non dal codice personalizzato, impostare nel codice personalizzato la variabile di flag CustomProcessingCancelled dei parametri imageSavingInfo. Essa segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, come se non esistesse alcun codice personalizzato esterno. Rappresenta le informazioni sull'immagine salvata che possono essere usate nel codice personalizzato; deve restituire una stringa che rappresenta l'URL dell'immagine da inserire nello SVG."
type: docs
weight: 10420
url: /it/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

Alla proprietà di questo tipo è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione del salvataggio esterno dell'immagine estratta da SVG generato da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (ad esempio il salvataggio personalizzato su stream o su disco) può essere eseguita nel codice personalizzato e tale codice deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nello SVG generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non verrà utilizzato. Se, per qualche motivo, l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Essa segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, come se non esistesse alcun codice personalizzato esterno. Rappresenta le informazioni sull'immagine salvata che possono essere usate nel codice personalizzato; deve restituire una stringa che rappresenta l'URL dell'immagine da inserire nello SVG.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Vedi anche

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


