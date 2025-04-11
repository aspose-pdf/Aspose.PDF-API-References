---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. Questo campo può contenere un metodo personalizzato che restituisce un URL o un modello di URL se la generazione multipagina è attivata - vedere i dettagli di seguito sull'argomento CSS come dovrebbe essere inserito nel risultato HTML generato. Ad esempio, se desideri che il convertitore inserisca un URL specifico invece del nome del file CSS standard nel CSS generato, allora dovresti semplicemente creare e inserire in questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non un URL esatto del CSS ma piuttosto una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina con la funzione string.Format() all'interno del convertitore) può essere risolta in un URL per il CSS di questa o quella pagina. Esempi di stringhe di ritorno attese in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')
type: docs
weight: 300
url: /it/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Campo HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Questo campo può contenere un metodo personalizzato che restituisce un URL (o un modello di URL se la generazione multipagina è attivata - vedere i dettagli di seguito) del soggetto CSS come dovrebbe essere inserito nel risultato HTML generato. Ad esempio, se desideri che il convertitore inserisca un URL specifico invece del nome del file CSS standard nel CSS generato, allora dovresti semplicemente creare e inserire in questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non un URL esatto del CSS ma piuttosto una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina con la funzione string.Format() all'interno del convertitore) può essere risolta in un URL per il CSS di questa o quella pagina. Esempi di stringhe di ritorno attese in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Vedi Anche

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)