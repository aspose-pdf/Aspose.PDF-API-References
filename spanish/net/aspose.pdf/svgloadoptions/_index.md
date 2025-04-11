---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.SvgLoadOptions. Representa opciones para cargar/importar archivos SVG en un documento PDF
type: docs
weight: 10210
url: /es/net/aspose.pdf/svgloadoptions/
---
## Clase SvgLoadOptions

Representa opciones para cargar/importar archivos SVG en un documento PDF.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Ajusta el tamaño de la página PDF al tamaño SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtiene o establece un indicador para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente, por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia deshabilitan la incrustación para esta fuente. Por defecto `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa el formato de archivo que describe [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Obtiene o establece la información de la página que debe aplicarse durante la carga del documento. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica ya sea Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo, el usuario también puede devolver Abort en cuyo caso la operación de carga debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Permite seleccionar el motor de conversión que se utilizará durante la conversión. Actualmente, el nuevo motor está en etapa de pruebas B, por lo que este valor se establece por defecto en ConversionEngines.LegacyEngine |

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)