---
title: System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum
linktitle: X509KeyStorageFlags
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum. Defines how to store key in C++.'
type: docs
weight: 2100
url: /cpp/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Defines how to store key.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| DefaultKeySet | 0 | Use default key set. |
| UserKeySet | 1 | Use user-associated store instead of machine-local one. |
| MachineKeySet | 2 | Use local machine store instead of user one. |
| Exportable | 4 | Marks imported keys as exportable. |
| UserProtected | 8 | Notify user that the key is being used. |
| PersistKeySet | 16 | The key is persisted when importing certificate. |

## See Also

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
