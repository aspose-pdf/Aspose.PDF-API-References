---
title: System::Security::Cryptography::ECDsaBotan::VerifyHash method
linktitle: VerifyHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsaBotan::VerifyHash method. Checks data signature in C++.'
type: docs
weight: 1500
url: /cpp/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash method


Checks data signature.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash calculated for received data. |
| signature | ByteArrayPtr | Signature as received. |

### ReturnValue

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
