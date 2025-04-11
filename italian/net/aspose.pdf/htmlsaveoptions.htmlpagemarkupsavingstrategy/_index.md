---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Il risultato della conversione può contenere una o più pagine HTML che possono anche fare riferimento a file esterni come immagini o font. Puoi assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ricevuta (HTML stesso) che è stata creata durante la conversione. In tal caso, l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio del markup delle pagine HTML devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel caso deve essere eseguita per qualche motivo dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, nello stesso modo in cui se non ci fosse alcun codice di salvataggio personalizzato esterno.
type: docs
weight: 5680
url: /it/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy

Il risultato della conversione può contenere una o più pagine HTML (che possono anche fare riferimento a file esterni come immagini o font). Puoi assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ricevuta (HTML stesso) che è stata creata durante la conversione. In tal caso, l'elaborazione (come il salvataggio in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio del markup della pagina HTML devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel caso deve essere eseguita per qualche motivo dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, nello stesso modo in cui se non ci fosse alcun codice di salvataggio personalizzato esterno.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | rappresenta i dati che possono essere utilizzati per il salvataggio o l'elaborazione della pagina HTML fornita |

### Vedi Anche

* classe [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)