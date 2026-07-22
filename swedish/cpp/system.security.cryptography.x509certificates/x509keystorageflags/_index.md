---
title: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum"
linktitle: "X509KeyStorageFlags"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum. Definierar hur nyckeln lagras i C++."
type: docs
weight: 2100
url: /sv/cpp/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Definierar hur nyckeln ska lagras.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| DefaultKeySet | 0 | Använd standardnyckeluppsättning. |
| UserKeySet | 1 | Använd lagring som är knuten till användaren istället för maskinlokal. |
| MachineKeySet | 2 | Använd lokal maskinlagring istället för användarens. |
| Exportable | 4 | Markerar importerade nycklar som exportbara. |
| UserProtected | 8 | Meddela användaren att nyckeln används. |
| PersistKeySet | 16 | Nyckeln bevaras när certifikatet importeras. |

## Se även

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
