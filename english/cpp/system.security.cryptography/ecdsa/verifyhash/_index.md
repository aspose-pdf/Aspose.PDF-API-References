---
title: System::Security::Cryptography::ECDsa::VerifyHash method
linktitle: VerifyHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsa::VerifyHash method. Checks data signature in C++.'
type: docs
weight: 1000
url: /cpp/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash method


Checks data signature.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash calculated for received data. |
| signature | ByteArrayPtr | Signature as received. |

### ReturnValue

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
