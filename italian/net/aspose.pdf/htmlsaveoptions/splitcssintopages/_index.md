---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "HtmlSaveOptions property. Quando la modalità multipagina è selezionata, cioè SplitIntoPages è true, questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita questo attributo è false, quindi verrà creato un unico CSS comune per tutte le pagine generate. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto maggiore della dimensione di un unico grande file CSS, poiché nel primo caso le classi CSS sono duplicate in diversi file per ciascuna pagina. Pertanto questa impostazione è consigliata solo quando si è interessati a elaborare in futuro ogni pagina HTML in modo indipendente e, di conseguenza, la dimensione del CSS di ciascuna pagina separata è la questione più critica."
type: docs
weight: 190
url: /it/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

Quando è selezionata la modalità multipagina (ad es. 'SplitIntoPages' è 'true'), questo attributo definisce se deve essere creato un file CSS separato per ogni pagina HTML risultante. Per impostazione predefinita questo attributo è false, quindi viene creato un unico CSS comune per tutte le pagine generate. La dimensione complessiva di tutti i CSS generati in questa modalità (un CSS per pagina) è solitamente molto superiore alla dimensione di un unico grande file CSS, poiché nel primo caso le classi CSS sono duplicate in diversi file CSS per ciascuna pagina. Pertanto questa impostazione è consigliata solo quando si è interessati all'elaborazione futura di ogni pagina HTML in modo indipendente, e quindi la dimensione del CSS di ciascuna pagina presa singolarmente è il problema più critico.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Vedi anche

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


