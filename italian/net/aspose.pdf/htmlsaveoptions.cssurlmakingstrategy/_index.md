---
title: "Delegato HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa la creazione dell'URL del CSS riferito nel documento HTML generato. Es. se si desidera rendere il CSS riferito in HTML, ad es. come otherPage.ASPXCssIDzjjkklj, allora tale strategia personalizzata deve restituire otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /it/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

È possibile assegnare a questa proprietà un delegato creato da un metodo personalizzato che implementa la creazione dell'URL del CSS riferito nel documento HTML generato. Es. se si desidera rendere il CSS riferito in HTML, ad es. come "otherPage.ASPX?CssID=zjjkklj", allora tale strategia personalizzata deve restituire "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | rappresenta un insieme di dati che può essere utilizzato per la generazione dell'URL del CSS |

### Valore di ritorno

deve restituire una stringa che rappresenta l'URL del CSS o il modello di URL

### Vedi anche

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


