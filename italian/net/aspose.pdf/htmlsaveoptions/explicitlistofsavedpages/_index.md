---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: Proprietà HtmlSaveOptions. Con questa proprietà puoi definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Ad esempio, i numeri validi delle pagine devono essere presi dall'intervallo 1...NumberOfPagesInConvertedDocument. L'ordine di apparizione delle pagine in questo elenco non influisce sul loro ordine nelle pagine HTML risultanti; nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF sorgente. Se questo elenco è nullo, come è per impostazione predefinita, tutte le pagine verranno convertite. Se un numero di pagina di questo elenco esce dall'intervallo delle pagine presenti (1-[amountOfPagesInDocument]), verrà generata un'eccezione.
type: docs
weight: 70
url: /it/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## Proprietà HtmlSaveOptions.ExplicitListOfSavedPages

Con questa proprietà puoi definire esplicitamente quali pagine del documento devono essere convertite. Le pagine in questo elenco devono avere numeri basati su 1. Ad esempio, i numeri validi delle pagine devono essere presi dall'intervallo (1...[NumberOfPagesInConvertedDocument]). L'ordine di apparizione delle pagine in questo elenco non influisce sul loro ordine nella/e pagina/e HTML risultante/i; nelle pagine risultanti andranno sempre nell'ordine in cui sono presenti nel PDF sorgente. Se questo elenco è nullo (come è per impostazione predefinita), tutte le pagine verranno convertite. Se un numero di pagina di questo elenco esce dall'intervallo delle pagine presenti (1-[amountOfPagesInDocument]), verrà generata un'eccezione.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Vedi Anche

* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)