---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A la propiedad de tal tipo se le puede asignar un delegado creado a partir de un método personalizado que implementa el procesamiento del guardado externo de la imagen que fue extraída del SVG creado a partir de PDF y debe ser guardada como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como el guardado hecho a mano en un flujo o en disco) puede realizarse en ese código personalizado y ese código personalizado debe devolver una ruta (o cualquier otra cadena sin comillas) que será incorporada posteriormente en el SVG generado en lugar de la ruta original supuesta a ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben ser emprendidas en el código del método suministrado, porque el guardado del resultado en el código del convertidor no será utilizado. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable de parámetros 'imageSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben ser realizados en el convertidor mismo como si no hubiera ningún código personalizado externo. Representa información sobre la imagen guardada que puede ser utilizada en el código personalizado y debe devolver una cadena que representa la URL de la imagen que será colocada en el SVG.
type: docs
weight: 10240
url: /es/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## Delegado SvgSaveOptions.EmbeddedImagesSavingStrategy

A la propiedad de tal tipo se le puede asignar un delegado creado a partir de un método personalizado que implementa el procesamiento del guardado externo de la imagen que fue extraída del SVG creado a partir de PDF y debe ser guardada como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como el guardado hecho a mano en un flujo o en disco) puede realizarse en ese código personalizado y ese código personalizado debe devolver una ruta (o cualquier otra cadena sin comillas) que será incorporada posteriormente en el SVG generado en lugar de la ruta original supuesta a ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben ser emprendidas en el código del método suministrado, porque el guardado del resultado en el código del convertidor no será utilizado. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable de parámetros 'imageSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben ser realizados en el convertidor mismo como si no hubiera ningún código personalizado externo. Representa información sobre la imagen guardada que puede ser utilizada en el código personalizado y debe devolver una cadena que representa la URL de la imagen que será colocada en el SVG.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Ver También

* clase [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* clase [SvgSaveOptions](../svgsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)