---
title: CustomStrategyOfEmbeddedImagesSaving
second_title: Referencia de API de Aspose.PDF para .NET
description: Este campo puede contener una estrategia de guardado que se debe usar si está presente durante la conversión para el manejo personalizado de imágenes externas referenciadas creadas archivos como BMP o JPEG incrustados incrustados en SVG guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa el URI deseable del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por algún motivo debe realizarse mediante el propio código del convertidor no en el código personalizado establezca en el indicador de código personalizado CustomProcessingCancelled de la variable del parámetro imageSavingInfo Le indica al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo .
type: docs
weight: 30
url: /es/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Este campo puede contener una estrategia de guardado que se debe usar (si está presente) durante la conversión para el manejo personalizado de imágenes externas referenciadas creadas archivos (como BMP o JPEG incrustados) incrustados en SVG guardado. Esa estrategia debe procesar recursos y devolver una cadena que representa el URI deseable del recurso guardado en el SVG generado. Si el procesamiento de este o aquel archivo por algún motivo debe realizarse mediante el propio código del convertidor, no en el código personalizado, establezca en el indicador de código personalizado 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo' Le indica al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo .

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Ver también

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy)
* class [SvgSaveOptions](../../svgsaveoptions)
* espacio de nombres [Aspose.Pdf](../../svgsaveoptions)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->