---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Si la propiedad SplitToPages de HtmlSaveOptions está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión de PDF a HTML. Esta clase representa un conjunto de datos relacionados con el guardado personalizado del marcado de una página HTML durante la conversión de PDF a HTML.
type: docs
weight: 5670
url: /es/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Clase HtmlSaveOptions.HtmlPageMarkupSavingInfo

Si la propiedad SplitToPages de HtmlSaveOptions está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión de PDF a HTML. Esta clase representa un conjunto de datos relacionados con el guardado personalizado del marcado de una página HTML durante la conversión de PDF a HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Campos

| Nombre | Descripción |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Establecido por el convertidor. Representa el HTML guardado como flujo. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Debe ser establecido en el código personalizado cuando sea necesario. Esta bandera debe establecerse en "true" en el código personalizado si por alguna razón el marcado HTML proporcionado debe ser procesado no con código personalizado sino con el código del convertidor en la forma estándar para el convertidor. Por lo tanto, establecer esta bandera en el código personalizado significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo por sí mismo. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Establecido por el convertidor. Si se establece la propiedad SplitToPages, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad contiene el ordinal del archivo de la página HTML guardada. La propiedad puede ser utilizada en la lógica del código personalizado para decidir cómo procesar o dónde guardar la página HTML y si la división en páginas está desactivada, este valor siempre contiene '1' ya que en tal caso solo se genera una gran página HTML para todo el documento fuente. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Establecido por el convertidor. Si se establece la propiedad SplitToPages, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad indica al código personalizado desde qué página del PDF original se creó el marcado HTML guardado. Si el número de página original por alguna razón es desconocido o SplitOnPages=false, entonces esta propiedad siempre contiene '0', lo que indica que el convertidor no puede proporcionar el número exacto de la página original del PDF para el archivo de marcado HTML proporcionado. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede ser utilizado en el código personalizado para decidir cómo procesar o dónde guardar el contenido. |

### Véase también

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)