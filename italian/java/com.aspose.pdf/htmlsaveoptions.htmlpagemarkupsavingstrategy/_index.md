---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il risultato della conversione può contenere una o più pagine HTML (che possono anche referenziare file esterni come immagini o font). È possibile assegnare a questa proprietà un delegato creato da."
type: docs
weight: 2110
url: /it/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

Il risultato della conversione può contenere una o più pagine HTML (che possono anche referenziare file esterni come immagini o font). È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa l'elaborazione della pagina HTML ottenuta (HTML stesso) creata durante la conversione. In tal caso l'elaborazione (come il salvataggio su stream o disco) può essere eseguita nel codice personalizzato. In tal caso tutte le azioni necessarie per il salvataggio del markup della pagina HTML devono essere eseguite nel codice del metodo fornito, poiché il salvataggio del risultato nel codice del convertitore non verrà utilizzato. Se per qualche motivo l'elaborazione in questo o quel caso deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile parametro 'htmlSavingInfo': segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso, come se non esistesse alcun codice di salvataggio personalizzato esterno.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Metodo interno beginInvoke |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Metodo interno endInvoke |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Metodo invocato |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Metodo interno beginInvoke

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Metodo interno endInvoke

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Metodo invocato
