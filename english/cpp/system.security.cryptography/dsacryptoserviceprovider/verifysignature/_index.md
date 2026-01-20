---
title: System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature method. Verify DSA signature for the specified data in C++.'
type: docs
weight: 1900
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature method


Verify [DSA](../../dsa/) signature for the specified data.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) signed with **rgb_signature**. |
| rgb_signature | ByteArrayPtr | [DSA](../../dsa/) signature. |

### ReturnValue

true - if **rgb_signature** matches the [DSA](../../dsa/) signature computed on **rgb_hash**, otherwise - false.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
