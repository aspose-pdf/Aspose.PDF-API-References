---
title: System::Net::Security::EncryptionPolicy enum
linktitle: EncryptionPolicy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::EncryptionPolicy enum. Enumerates the encryption policies in C++.'
type: docs
weight: 400
url: /cpp/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum


Enumerates the encryption policies.

```cpp
enum class EncryptionPolicy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RequireEncryption | 0 | Require encryption and never allow a 'Null' cipher. |
| AllowNoEncryption | 1 | Prefer using full encryption but a 'Null' cipher can be used if the server agrees. |
| NoEncryption | 2 | Allow no encryption and request that a 'Null' cipher be used if the other endpoint can handle a 'Null' cipher. |

## See Also

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
