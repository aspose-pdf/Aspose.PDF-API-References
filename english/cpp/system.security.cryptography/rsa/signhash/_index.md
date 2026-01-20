---
title: System::Security::Cryptography::RSA::SignHash method
linktitle: SignHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::SignHash method. Computes the signature for the specified hash value in C++.'
type: docs
weight: 1100
url: /cpp/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash method


Computes the signature for the specified hash value.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash value. |
| hash_algorithm | HashAlgorithmName | Hash algorithm. |
| padding | SharedPtr\<RSASignaturePadding\> | Padding mode. return [RSA](../) signature for the specified hash. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
