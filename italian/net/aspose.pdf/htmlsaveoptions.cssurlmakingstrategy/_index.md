---
title: HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF per .NET API Reference
description: È possibile assegnare a questa proprietà un delegato creato dal metodo personalizzato che implementa la creazione dellURL del CSS a cui si fa riferimento nel documento HTML generato. Fe se si desidera fare riferimento CSS in HTML fe come otherPage.ASPXCssIDzjjkklj Quindi tale strategia personalizzata deve restituire otherPage.ASPXCssIDzjjkklj
type: docs
weight: 3470
url: /it/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

È possibile assegnare a questa proprietà un delegato creato dal metodo personalizzato che implementa la creazione dell'URL del CSS a cui si fa riferimento nel documento HTML generato. Fe se si desidera fare riferimento CSS in HTML fe come "otherPage.ASPX?CssID=zjjkklj" Quindi tale strategia personalizzata deve restituire "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | rappresenta un insieme di dati che possono essere utilizzati per la generazione dell'URL di CSS |

### Valore di ritorno

deve restituire una stringa che rappresenta l'URL del CSS o il modello dell'URL

### Guarda anche

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->