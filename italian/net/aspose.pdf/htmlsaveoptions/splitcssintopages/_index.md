---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: Proprietà HtmlSaveOptions. Quando è selezionata la modalità multipagina, cioè 'SplitIntoPages' è vero, allora questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita, questo attributo è falso, quindi verrà creato un grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità è solitamente molto maggiore della dimensione di un grande file CSS, perché nel primo caso le classi CSS sono duplicati in questo caso in diversi file CSS per ogni pagina. Quindi, questa impostazione è peggiore da utilizzare solo quando sei interessato al futuro trattamento di ogni pagina HTML in modo indipendente e quindi la dimensione del CSS di ciascuna pagina presa separatamente è la questione più critica.
type: docs
weight: 190
url: /it/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## Proprietà HtmlSaveOptions.SplitCssIntoPages

Quando è selezionata la modalità multipagina (cioè 'SplitIntoPages' è 'true'), allora questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita, questo attributo è falso, quindi verrà creato un grande CSS comune per tutte le pagine create. La dimensione complessiva di tutti i CSS generati in questa modalità (uno CSS per pagina) è solitamente molto maggiore della dimensione di un grande file CSS, perché nel primo caso le classi CSS sono duplicati in questo caso in diversi file CSS per ogni pagina. Quindi, questa impostazione è peggiore da utilizzare solo quando sei interessato al futuro trattamento di ogni pagina HTML in modo indipendente e quindi la dimensione del CSS di ciascuna pagina presa separatamente è la questione più critica.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Vedi Anche

* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)