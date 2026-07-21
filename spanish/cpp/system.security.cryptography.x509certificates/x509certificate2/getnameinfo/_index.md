---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo método"
linktitle: "GetNameInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo método. Obtiene el nombre del sujeto o del emisor del certificado en C++."
type: docs
weight: 2100
url: /es/cpp/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo method


Obtiene el nombre del sujeto o del emisor del certificado.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name_type | X509NameType | Opciones de formato de nombre. |
| for_issuer | bool | Si es verdadero, devuelve el nombre del emisor; de lo contrario, devuelve el nombre del sujeto. |

### ReturnValue

Nombre del emisor o del sujeto formateado.

## Ver también

* Class [String](../../../system/string/)
* Enum [X509NameType](../../x509nametype/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
