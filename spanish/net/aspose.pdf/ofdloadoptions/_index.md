---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.OfdLoadOptions. Opciones de carga para el formato OFD
type: docs
weight: 7060
url: /es/net/aspose.pdf/ofdloadoptions/
---
## Clase OfdLoadOptions

Opciones de carga para el formato OFD.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento del enum ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

### Véase También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)