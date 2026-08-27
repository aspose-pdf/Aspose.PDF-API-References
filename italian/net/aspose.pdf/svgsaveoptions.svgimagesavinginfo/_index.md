---
title: "Classe SvgSaveOptions.SvgImageSavingInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagine di risorse esterne durante la conversione da PDF a HTML"
type: docs
weight: 10440
url: /it/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Questa classe rappresenta un insieme di dati relativi al salvataggio del file immagine di risorse esterne durante la conversione da PDF a HTML.

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Questo flag deve essere impostato su "true" nel codice personalizzato se, per qualche motivo, il file proposto deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso secondo il modo standard del convertitore. Quindi, impostare il flag su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (sia per il salvataggio che per la denominazione del file di riferimento). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

### Vedi anche

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


