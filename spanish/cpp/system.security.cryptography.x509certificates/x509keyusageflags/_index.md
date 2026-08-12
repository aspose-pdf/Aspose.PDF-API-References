---
title: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum"
linktitle: "X509KeyUsageFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum. Define cómo se puede usar la clave del certificado en C++."
type: docs
weight: 2200
url: /es/cpp/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Define cómo se puede usar la clave del certificado.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | No hay parámetros de uso de clave. |
| EncipherOnly | 1 | La clave solo puede usarse para cifrado. |
| CrlSign | 2 | La clave puede usarse para firmar una lista de revocación de certificados. |
| KeyCertSign | 4 | La clave puede usarse para firmar certificados. |
| KeyAgreement | 8 | La clave puede usarse para determinar el acuerdo de claves. |
| DataEncipherment | 16 | La clave puede usarse para el cifrado de datos. |
| KeyEncipherment | 32 | La clave puede usarse para el cifrado de claves. |
| NonRepudiation | 64 | La clave puede usarse para autenticación. |
| DigitalSignature | 128 | La clave puede usarse como firma digital. |
| DecipherOnly | 32768 | La clave solo puede usarse para descifrado. |

## Ver también

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
