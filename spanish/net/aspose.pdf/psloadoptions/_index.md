---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PsLoadOptions. Representa opciones para cargar/importar un archivo .mht en un documento pdf
type: docs
weight: 9730
url: /es/net/aspose.pdf/psloadoptions/
---
## Clase PsLoadOptions

Representa opciones para cargar/importar un archivo .mht en un documento pdf.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Obtiene o establece las rutas de las carpetas de fuentes. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

### Véase también

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)