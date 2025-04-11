---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.CdrLoadOptions. La clase describe las opciones de carga de CDR
type: docs
weight: 2960
url: /es/net/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions class

La clase describe las opciones de carga de CDR.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | El constructor predeterminado. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)