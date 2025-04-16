---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. El resultado de la conversión puede contener una o varias páginas HTML. Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa el procesamiento de una página HTML que fue creado durante la conversión. En tal caso, el procesamiento puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar la página HTML deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este o aquel caso, por alguna razón, debe hacerse por el propio código del convertidor, no en el código personalizado, por favor, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': esto señalará al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben hacerse en el propio convertidor de la misma manera que si no hubiera ningún código personalizado externo para el procesamiento.
type: docs
weight: 270
url: /es/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## Campo HtmlSaveOptions.CustomHtmlSavingStrategy

El resultado de la conversión puede contener una o varias páginas HTML. Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa el procesamiento de una página HTML (para ser preciso - markup-HTML, sin archivos vinculados externos, si los hay) que fue creado durante la conversión. En tal caso, el procesamiento (como el guardado del HTML de la página en un flujo o disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar la página HTML deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este o aquel caso, por alguna razón, debe hacerse por el propio código del convertidor, no en el código personalizado, por favor, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': esto señalará al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben hacerse en el propio convertidor de la misma manera que si no hubiera ningún código personalizado externo para el procesamiento.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Ver También

* delegado [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* clase [HtmlSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)