---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML.
type: docs
weight: 10260
url: /es/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | El constructor predeterminado. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Establecido por el convertidor. Representa el contenido binario del archivo guardado. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Esta bandera debe establecerse en "true" en el código personalizado si por alguna razón el archivo propuesto debe ser procesado no con código personalizado, sino con el código del convertidor en su forma estándar. Por lo tanto, establecerlo en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo por sí mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser utilizado en el código personalizado para decidir qué se debe hacer. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)