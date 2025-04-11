---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: Campo SvgSaveOptions. Este campo puede contener la estrategia de guardado que debe usarse si está presente durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas, como BMP o JPEG incrustados en el SVG guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa la URI deseada del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo y no en el código personalizado, por favor establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben ser realizados en el convertidor mismo como si no hubiera ningún código personalizado externo.
type: docs
weight: 30
url: /es/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## Campo SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) en el SVG guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa la URI deseada del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben ser realizados en el convertidor mismo como si no hubiera ningún código personalizado externo.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Ver También

* delegado [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* clase [SvgSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)