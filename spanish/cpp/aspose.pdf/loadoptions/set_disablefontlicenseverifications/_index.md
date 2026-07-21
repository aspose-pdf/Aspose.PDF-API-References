---
title: "Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications método"
linktitle: "set_DisableFontLicenseVerifications"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications método. Establece una bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando es true, permite ejecutar operaciones con la fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF aunque las reglas de licencia desactiven la incrustación de esa fuente. Por defecto es false en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf/loadoptions/set_disablefontlicenseverifications/
---
## LoadOptions::set_DisableFontLicenseVerifications method


Establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando **true**

, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de la licencia desactivan la incrustación para esa fuente. Por defecto **false**

.

```cpp
void Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications(bool value)
```

## Observaciones


Tenga cuidado al usar esta bandera. Cuando está activada significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencias o leyes. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor.
## Ver también

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
