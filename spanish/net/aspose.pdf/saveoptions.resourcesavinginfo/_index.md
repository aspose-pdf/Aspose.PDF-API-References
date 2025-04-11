---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.SaveOptionsResourceSavingInfo. Esta clase representa un conjunto de datos relacionados con el guardado de archivos de recursos externos que ocurre durante la conversión de PDF a otro formato, por ejemplo, HTML.
type: docs
weight: 9940
url: /es/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## Clase SaveOptions.ResourceSavingInfo

Esta clase representa un conjunto de datos relacionados con el guardado de archivos de recursos externos que ocurre durante la conversión de PDF a otro formato (por ejemplo, HTML)

```csharp
public class ResourceSavingInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo |

## Campos

| Nombre | Descripción |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Establecido por el convertidor. Representa el contenido binario del archivo guardado. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Esta bandera debe establecerse en "true" en el código personalizado si por alguna razón el archivo propuesto debe ser procesado no con código personalizado, sino con el código del convertidor en su forma estándar. Por lo tanto, establecerlo en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo por sí mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar ese archivo |

### Véase también

* clase [SaveOptions](../saveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)