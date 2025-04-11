---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: El resultado de la conversión puede contener una o varias páginas HTML que también pueden hacer referencia a archivos externos como imágenes o fuentes. Puedes asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de la página HTML que se creó durante la conversión. En tal caso, el procesamiento, como el guardado en un flujo o en disco, puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar el marcado de las páginas HTML deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este o aquel caso, por alguna razón, debe realizarse por el código del convertidor mismo y no en el código personalizado, establece en el código personalizado la bandera CustomProcessingCancelled de la variable de parámetros htmlSavingInfo; esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el convertidor mismo, de la misma manera que si no hubiera ningún código de guardado personalizado externo.
type: docs
weight: 5680
url: /es/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
| --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | representa datos que pueden ser utilizados para guardar o procesar la página HTML proporcionada |

### Ver También

* clase [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)