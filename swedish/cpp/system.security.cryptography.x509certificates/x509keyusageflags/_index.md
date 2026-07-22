---
title: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum"
linktitle: "X509KeyUsageFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum. Definierar hur certifikatnyckeln kan användas i C++."
type: docs
weight: 2200
url: /sv/cpp/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Definierar hur certifikatnyckeln kan användas.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Inga nyckelanvändningsparametrar. |
| EncipherOnly | 1 | Nyckeln kan endast användas för kryptering. |
| CrlSign | 2 | Nyckeln kan användas för att signera en certifikatåterkallningslista. |
| KeyCertSign | 4 | Nyckeln kan användas för att signera certifikat. |
| KeyAgreement | 8 | Nyckeln kan användas för att bestämma nyckelavtal. |
| DataEncipherment | 16 | Nyckeln kan användas för datakryptering. |
| KeyEncipherment | 32 | Nyckeln kan användas för nyckelkryptering. |
| NonRepudiation | 64 | Nyckeln kan användas för autentisering. |
| DigitalSignature | 128 | Nyckeln kan användas som en digital signatur. |
| DecipherOnly | 32768 | Nyckeln kan endast användas för dekryptering. |

## Se även

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
