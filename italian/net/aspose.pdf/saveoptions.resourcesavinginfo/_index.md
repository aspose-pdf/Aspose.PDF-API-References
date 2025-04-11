---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Questa classe rappresenta un insieme di dati relativi al salvataggio di risorse esterne che avviene durante la conversione del PDF in un altro formato, ad esempio, HTML.
type: docs
weight: 9940
url: /it/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## Classe SaveOptions.ResourceSavingInfo

Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in un altro formato (ad esempio HTML)

```csharp
public class ResourceSavingInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Questo flag deve essere impostato su "true" nel codice personalizzato se per qualche motivo il file proposto deve essere elaborato non con il codice personalizzato ma con il codice stesso del convertitore in modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo da solo (in entrambi i sensi - per salvarlo da qualche parte e per nominare nel file di riferimento). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file |

### Vedi Anche

* classe [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)