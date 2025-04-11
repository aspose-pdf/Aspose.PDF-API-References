---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML
type: docs
weight: 5640
url: /es/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## Clase HtmlSaveOptions.HtmlImageSavingInfo

Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Establecido por el convertidor. Representa el contenido binario del archivo guardado. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Esta bandera debe establecerse en "true" en el código personalizado si por alguna razón el archivo propuesto debe ser procesado no con el código personalizado, sino con el código del convertidor en la forma estándar para el convertidor. Por lo tanto, establecerlo en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo por sí mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Indica al código personalizado a qué página del conjunto generado de archivos de página HTML pertenece la imagen guardada. Si la división en páginas está desactivada, este valor siempre contiene '1', ya que en tal caso solo se genera una página HTML. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser utilizado en el código personalizado para decidir qué se debe hacer. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | La imagen guardada puede pertenecer al HTML en sí o puede ser extraída de SVG incrustado en HTML. Esta propiedad puede indicar al código personalizado qué tipo de padre tiene la imagen procesada. Establecido por el convertidor y puede ser utilizado en el código personalizado para decidir qué se debe hacer con esa imagen (por ejemplo, el código personalizado puede decidir dónde guardar la imagen o cómo debe ser referenciada en el contenido del padre). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Indica al código personalizado a qué página del documento PDF original pertenece la imagen guardada. Dado que es posible que no se guarden todas las páginas del documento original, este valor nos indica el número de página anfitriona en el PDF original. Si el número de página original por alguna razón es desconocido, siempre devuelve '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo. |

### Véase también

* clase [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)