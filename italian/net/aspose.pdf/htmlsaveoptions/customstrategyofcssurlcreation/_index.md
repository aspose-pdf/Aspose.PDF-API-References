---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Campo HtmlSaveOptions. Questo campo può contenere un metodo personalizzato che restituisce un URL o un modello di URL se la generazione multipagina è attiva; vedere i dettagli qui sotto sul CSS di riferimento così come dovrebbe essere inserito nell'HTML generato. Per esempio, se vuoi che il convertitore inserisca un URL specifico al posto del nome file CSS standard nel CSS generato, devi semplicemente creare e assegnare a questa proprietà un metodo che generi l'URL desiderato. Se il flag SplitCssIntoPages è impostato, allora questa strategia personalizzata, se presente, deve restituire non l'URL esatto del CSS ma una stringa modello che, dopo la sostituzione del segnaposto con il numero di pagina tramite la funzione string.Format all'interno del convertitore, può essere risolta in un URL per il CSS di quella pagina o di un'altra. Esempi di stringhe di ritorno attese in tal caso sono SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /it/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Questo campo può contenere un metodo personalizzato che restituisce l'URL (o il modello di URL se la generazione multipagina è attiva – vedere i dettagli sotto) del CSS di riferimento da inserire nell'HTML risultato generato. Per esempio, se si desidera che il convertitore inserisca un URL specifico al posto del nome file CSS standard nell'HTML generato, è sufficiente creare e assegnare a questa proprietà un metodo che genera l'URL desiderato. Se il flag 'SplitCssIntoPages' è impostato, allora questa strategia personalizzata (se presente) deve restituire non l'URL esatto del CSS ma una stringa modello che (dopo la sostituzione del segnaposto con il numero di pagina tramite la funzione string.Format() all'interno del convertitore) può essere risolta nell'URL del CSS per quella pagina. Esempi di stringa di ritorno attesa in tal caso sono: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Vedi anche

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


