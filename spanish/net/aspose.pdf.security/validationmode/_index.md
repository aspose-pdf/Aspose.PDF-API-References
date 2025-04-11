---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMode de Aspose.Pdf.Security. Especifica el modo de validación para los procesos de validación de firmas PDF
type: docs
weight: 10060
url: /es/net/aspose.pdf.security/validationmode/
---
## Enumeración ValidationMode

Especifica el modo de validación para los procesos de validación de firmas PDF.

```csharp
public enum ValidationMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | `0` | Representa un modo en el que no se realiza la validación. |
| SoloComprobar | `1` | Representa el modo en el que se realiza la validación, pero su resultado no afecta la validación de la firma digital. Puedes comprobar el resultado de la validación tú mismo. |
| Estricto | `2` | Representa el modo en el que se realiza la validación y su resultado afecta la validación de la firma digital. Si el certificado no pudo ser verificado, entonces la firma digital se considerará inválida. Puedes comprobar el resultado de la validación tú mismo. |

### Ver También

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)