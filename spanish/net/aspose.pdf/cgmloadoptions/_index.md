---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.CgmLoadOptions. Contiene opciones para cargar/importar un archivo CGM en un documento pdf
type: docs
weight: 3010
url: /es/net/aspose.pdf/cgmloadoptions/
---
## Clase CgmLoadOptions

Contiene opciones para cargar/importar un archivo CGM en un documento pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Crea opciones de carga predeterminadas para convertir un archivo CGM en un documento pdf. Tamaño de página pdf predeterminado - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Crea opciones de carga con un !:pageSize definido. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Obtiene o establece el tamaño de página de salida para la importación. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

### Véase también

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)