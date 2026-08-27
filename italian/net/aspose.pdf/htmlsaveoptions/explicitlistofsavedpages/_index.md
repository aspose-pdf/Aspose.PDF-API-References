---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "HtmlSaveOptions property. Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri validi delle pagine devono essere presi dall'intervallo 1...NumberOfPagesInConvertedDocument. L'ordine di apparizione delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti; le pagine risultanti saranno sempre nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è nullo, come avviene per impostazione predefinita, tutte le pagine saranno convertite. Se qualche numero di pagina in questo elenco supera l'intervallo delle pagine presenti (amountOfPagesInDocument), verrà sollevata un'eccezione."
type: docs
weight: 70
url: /it/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

Con questa proprietà è possibile definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Cioè, i numeri di pagina validi devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di comparsa delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti: nelle pagine risultanti verranno sempre visualizzate nell'ordine in cui sono presenti nel PDF di origine. Se questo elenco è null (come è impostato per impostazione predefinita), verranno convertite tutte le pagine. Se qualche numero di pagina di questo elenco supera l'intervallo delle pagine presenti (1-[amountOfPagesInDocument]), verrà generata un'eccezione.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Vedi anche

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


