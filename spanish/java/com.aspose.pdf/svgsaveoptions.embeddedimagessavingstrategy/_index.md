---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "A la propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de la imagen que se extrajo del SVG creado a partir del PDF."
type: docs
weight: 4730
url: /es/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

Para una propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de una imagen extraída de un SVG generado a partir de un PDF y que debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardado propio en un flujo o en disco) puede realizarse en ese código personalizado y dicho código debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al SVG generado en lugar de la ruta original supuesta del recurso de imagen. En este caso todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este u otro archivo, por alguna razón, debe ser realizado por el propio código del convertidor y no por el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto indica al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo.

## Métodos

| Método | Descripción |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
