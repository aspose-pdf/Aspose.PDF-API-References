---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: Propiedad LoadOptions. Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando es verdadero, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente; por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto, falso.
type: docs
weight: 10
url: /es/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## Propiedad LoadOptions.DisableFontLicenseVerifications

Obtiene o establece una bandera para deshabilitar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando `true`, permite ejecutar operaciones con fuentes que están prohibidas por una licencia de esta fuente; por ejemplo, permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación para esta fuente. Por defecto `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Observaciones

Tenga cuidado al usar esta bandera. Cuando se establece, significa que la persona que establece esta bandera asume toda la responsabilidad de posibles violaciones de licencia/ley. Así que lo asume bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor.

### Véase también

* clase [LoadOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)