---
title: CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF per .NET API Reference
description: Questo campo può contenere la strategia di salvataggio che deve essere utilizzata se presente durante la conversione per la gestione personalizzata delle immagini esterne di riferimento create file come BMP o JPEG incorporati incorporati in SVG salvati. Tale strategia deve elaborare le risorse e restituire la stringa che rappresenta lURI desiderabile della risorsa salvata nellSVG generato. Se lelaborazione di questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso non nel codice personalizzato impostare nel codice personalizzato flag CustomProcessingCancelled di imageSavingInfo del parametro variable Segnala al convertitore che tutti i passaggi necessari per lelaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno .
type: docs
weight: 30
url: /it/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata delle immagini esterne di riferimento create file (come BMP o JPEG incorporati) incorporati in SVG salvati. Tale strategia deve elaborare le risorse e restituire la stringa che rappresenta l'URI desiderabile della risorsa salvata nell'SVG generato. Se l'elaborazione di questo o quel file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non nel codice personalizzato, impostare nel codice personalizzato flag 'CustomProcessingCancelled' di 'imageSavingInfo' del parametro variable Segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno .

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Guarda anche

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy)
* class [SvgSaveOptions](../../svgsaveoptions)
* spazio dei nomi [Aspose.Pdf](../../svgsaveoptions)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
