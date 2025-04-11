---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo classe. Questa classe rappresenta un insieme di dati relativi al salvataggio dei file immagine delle risorse esterne durante la conversione da PDF a HTML
type: docs
weight: 10260
url: /it/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo classe

Questa classe rappresenta un insieme di dati relativi al salvataggio dei file immagine delle risorse esterne durante la conversione da PDF a HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | questo flag deve essere impostato su "true" nel codice personalizzato se per qualche motivo il file proposto deve essere elaborato non con codice personalizzato ma con il codice stesso del convertitore in modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo da solo (in entrambi i sensi - per salvarlo da qualche parte e per nominare nel file di riferimento). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere utilizzato nel codice personalizzato per decidere cosa dovrebbe essere fatto |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file |

### Vedi Anche

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)