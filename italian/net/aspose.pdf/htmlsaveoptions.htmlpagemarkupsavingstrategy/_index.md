---
title: "Delegato HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Il risultato della conversione può contenere una o più pagine HTML che possono anche fare riferimento a file esterni come immagini o font. È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ottenuta, creata durante la conversione. In tal caso, l'elaborazione, come il salvataggio su stream o su disco, può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio del markup delle pagine HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quello caso deve essere eseguita dal codice del convertitore stesso e non dal codice personalizzato, impostare nel codice personalizzato la variabile flag CustomProcessingCancelled dei parametri htmlSavingInfo; segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso nello stesso modo in cui sarebbe stato senza alcun codice di salvataggio personalizzato esterno."
type: docs
weight: 5810
url: /it/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

Il risultato della conversione può contenere una o più pagine HTML (che possono anche fare riferimento a file esterni come immagini o font). È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ottenuta (HTML stesso) creata durante la conversione. In tal caso, l'elaborazione (come il salvataggio su stream o su disco) può essere eseguita in quel codice personalizzato. In tal caso, tutte le azioni necessarie per il salvataggio del markup della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non sarà utilizzato. Se, per qualche motivo, l'elaborazione per questo o quello caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'htmlSavingInfo': segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso nello stesso modo in cui sarebbe stato senza alcun codice di salvataggio personalizzato esterno.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | rappresenta dati che possono essere usati per il salvataggio o l'elaborazione della pagina HTML fornita |

### Vedi anche

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


