---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. Il risultato della conversione può contenere una o più pagine HTML. Puoi assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML che è stata creata durante la conversione. In tal caso, l'elaborazione può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio della pagina HTML devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel caso deve essere eseguita per qualche motivo dal codice del convertitore stesso, non nel codice personalizzato, imposta nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': questo segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, allo stesso modo in cui se non ci fosse alcun codice personalizzato esterno per l'elaborazione.
type: docs
weight: 270
url: /it/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## Campo HtmlSaveOptions.CustomHtmlSavingStrategy

Il risultato della conversione può contenere una o più pagine HTML. Puoi assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una pagina HTML (per essere precisi - markup-HTML, senza file collegati esterni, se presenti) che è stata creata durante la conversione. In tal caso, l'elaborazione (come il salvataggio dell'HTML della pagina in stream o disco) può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio della pagina HTML devono essere intraprese nel codice del metodo fornito, perché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se l'elaborazione per questo o quel caso deve essere eseguita per qualche motivo dal codice del convertitore stesso, non nel codice personalizzato, imposta nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': questo segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, allo stesso modo in cui se non ci fosse alcun codice personalizzato esterno per l'elaborazione.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Vedi Anche

* delegato [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)