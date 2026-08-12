---
title: "Aspose::Pdf::Security::ValidationMethod enum"
linktitle: "ValidationMethod"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ValidationMethod enum. Representa un enum que define el método utilizado para la validación de certificados en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.security/validationmethod/
---
## ValidationMethod enum


Representa un enum que define el método utilizado para la validación de certificados.

```cpp
enum class ValidationMethod
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | 0 | Determina automáticamente el mejor método para la validación de certificados. |
| Ocsp | 1 | Utiliza el Protocolo de Estado de Certificado en Línea (OCSP) para la validación de certificados. OCSP es un protocolo que proporciona el estado de validación de un certificado al consultar directamente a la Autoridad de Certificación (CA) emisora. |
| Crl | 2 | Valida certificados utilizando el método de Lista de Revocación de Certificados (CRL). |
| Todo | 3 | Utiliza todos los métodos disponibles (OCSP y CRL) para la validación de certificados. |

## Ver también

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
