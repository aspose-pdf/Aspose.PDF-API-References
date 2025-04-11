---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: Campo SvgSaveOptions. Questo campo può contenere la strategia di salvataggio che deve essere utilizzata se presente durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate creati, come BMP o JPEG incorporati nel SVG salvato. Quella strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nel SVG generato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso e non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno.
type: docs
weight: 30
url: /it/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## Campo SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate (come BMP o JPEG incorporati) incorporati nel SVG salvato. Quella strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nel SVG generato. Se l'elaborazione per questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, e non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Vedi Anche

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)