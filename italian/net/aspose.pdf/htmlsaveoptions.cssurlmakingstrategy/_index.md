---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa la creazione dell'URL del CSS referenziato nel documento HTML generato. Ad esempio, se si desidera fare in modo che il CSS sia referenziato in HTML ad esempio come otherPage.ASPXCssIDzjjkklj, allora tale strategia personalizzata deve restituire otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /it/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Delegato HtmlSaveOptions.CssUrlMakingStrategy

È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa la creazione dell'URL del CSS referenziato nel documento HTML generato. Ad esempio, se si desidera fare in modo che il CSS sia referenziato in HTML ad esempio come "otherPage.ASPX?CssID=zjjkklj", allora tale strategia personalizzata deve restituire "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | rappresenta un insieme di dati che possono essere utilizzati per la generazione dell'URL del CSS |

### Valore di ritorno

deve restituire una stringa che rappresenta l'URL del CSS o il modello dell'URL

### Vedi anche

* classe [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)