---
title: "Classe SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.SaveOptionsResourceSavingInfo class. Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in qualche altro formato, ad es. HTML."
type: docs
weight: 10090
url: /it/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

Questa classe rappresenta un insieme di dati relativi al salvataggio di file di risorse esterne che si verifica durante la conversione di PDF in qualche altro formato (ad es. HTML)

```csharp
public class ResourceSavingInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Questo flag deve essere impostato su "true" nel codice personalizzato se, per qualche motivo, il file proposto deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso secondo il modo standard del convertitore. Quindi, impostare il flag su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (sia per il salvataggio che per la denominazione del file di riferimento). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

### Vedi anche

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


