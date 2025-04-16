---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A questa proprietà puoi assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di risorse esterne che sono state estratte da un PDF e devono essere salvate come risorsa esterna durante la conversione da PDF a HTML. In tal caso, l'elaborazione può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire un percorso che sarà successivamente incorporato nell'HTML generato invece del percorso originale previsto per quella risorsa immagine. In tal caso, tutte le azioni necessarie per il salvataggio dell'immagine devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'resourceSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno.
type: docs
weight: 5730
url: /it/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## Delegato HtmlSaveOptions.ResourceSavingStrategy

A questa proprietà puoi assegnare un delegato creato da un metodo personalizzato che implementa l'elaborazione di risorse esterne (Font o Immagine) che sono state estratte da un PDF e devono essere salvate come risorsa esterna durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato e quel codice personalizzato deve restituire un percorso (o qualsiasi altra stringa senza virgolette) che sarà successivamente incorporato nell'HTML generato invece del percorso originale previsto per quella risorsa immagine. In tal caso, tutte le azioni necessarie per il salvataggio dell'immagine devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'resourceSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | rappresenta un insieme di dati per il salvataggio della risorsa |

### Valore di ritorno

deve restituire l'URL della risorsa salvata che sarà utilizzato durante la generazione dell'HTML

### Vedi anche

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)