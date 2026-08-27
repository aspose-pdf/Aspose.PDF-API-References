---
title: "Delegato HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "A questa proprietà è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di una risorsa esterna resourceFont o Image estratta da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione, come il salvataggio in stream o su disco, può essere eseguita in quel codice personalizzato e tale codice deve restituire un percorso o qualsiasi altra stringa senza virgolette che verrà successivamente incorporata nell'HTML generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso e non dal codice personalizzato, impostare nel codice personalizzato la variabile flag CustomProcessingCancelled dei parametri resourceSavingInfo. Essa segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, come se non esistesse alcun codice personalizzato esterno."
type: docs
weight: 5860
url: /it/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

A questa proprietà è possibile assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di una risorsa esterna (Font o Image) estratta da PDF e che deve essere salvata come risorsa esterna durante la conversione da PDF a HTML. In tal caso l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato e tale codice deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che verrà successivamente incorporato nell'HTML generato al posto del percorso originale previsto per quella risorsa immagine. In tal caso tutte le azioni necessarie per il salvataggio dell'immagine devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se per qualche motivo l'elaborazione di questo o di quell'altro file deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato la variabile flag 'CustomProcessingCancelled' del parametro 'resourceSavingInfo'. Essa segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, come se non esistesse alcun codice personalizzato esterno.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | rappresenta un insieme di dati per il salvataggio della risorsa |

### Valore di ritorno

deve restituire l'URL della risorsa salvata che verrà utilizzato durante la generazione dell'HTML

### Vedi anche

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


