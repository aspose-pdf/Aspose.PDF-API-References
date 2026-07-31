---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Campo SvgSaveOptions. Questo campo può contenere una strategia di salvataggio che deve essere utilizzata, se presente, durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate creati, come BMP o JPEG incorporati nel SVG salvato. tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nello SVG generato. Se l'elaborazione di questo o di quell'altro file, per qualche motivo, deve essere eseguita dal codice del convertitore stesso e non dal codice personalizzato, impostare nel codice personalizzato il flag CustomProcessingCancelled della variabile dei parametri imageSavingInfo. Esso segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non esistesse alcun codice personalizzato esterno."
type: docs
weight: 30
url: /it/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file immagine esterni referenziati creati (come BMP o JPEG incorporati) incorporati nello SVG salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nello SVG generato. Se l'elaborazione di questo o di quell'altro file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Vedi anche

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


