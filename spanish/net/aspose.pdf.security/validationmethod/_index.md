---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMethod de Aspose.Pdf.Security. Representa un enum definido el método utilizado para la validación de certificados
type: docs
weight: 10050
url: /es/net/aspose.pdf.security/validationmethod/
---
## Enumeración ValidationMethod

Representa un enum definido el método utilizado para la validación de certificados.

```csharp
public enum ValidationMethod
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | Determina automáticamente el mejor método para la validación de certificados. |
| Ocsp | `1` | Utiliza el Protocolo de Estado de Certificado en Línea (OCSP) para la validación de certificados. OCSP es un protocolo que proporciona el estado de validación de un certificado consultando directamente a la Autoridad de Certificación (CA) emisora. |
| Crl | `2` | Valida certificados utilizando el método de Lista de Revocación de Certificados (CRL). |
| All | `3` | Utiliza todos los métodos disponibles (OCSP y CRL) para la validación de certificados. |

### Ver También

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)