---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Campo HtmlSaveOptions. Il risultato della conversione può contenere una o più HTMLpages. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una HTMLpage per generare markup HTML accurato senza file collegati esternamente, se presenti, creati durante la conversione. In tal caso operazioni come il salvataggio delle pagine HTML in stream o su disco possono essere eseguite in quel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quello caso deve essere eseguita dal codice del convertitore stesso e non dal codice personalizzato, impostare nel codice personalizzato la variabile flag CustomProcessingCancelled dei parametri htmlSavingInfo; essa segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, come se non esistesse alcun codice personalizzato esterno per l'elaborazione."
type: docs
weight: 270
url: /it/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Il risultato della conversione può contenere una o più pagine HTML. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione di una singola pagina HTML (in modo più preciso – markup HTML, senza file collegati esternamente, se presenti) generata durante la conversione. In tal caso l'elaborazione (come il salvataggio della pagina HTML in stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quel caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato la variabile flag 'CustomProcessingCancelled' del parametro 'htmlSavingInfo': segnalerà al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso, nello stesso modo in cui avverrebbe se non fosse presente alcun codice personalizzato esterno per l'elaborazione.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Vedi anche

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


