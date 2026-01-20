---
title: System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash method
linktitle: VerifyHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash method. Checks data signature in C++.'
type: docs
weight: 1800
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash method


Checks data signature.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hash calculated for received data. |
| str | const String\& | Name of hash algorithm used. |
| rgb_signature | const ByteArrayPtr\& | Signature as received. |

### ReturnValue

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
