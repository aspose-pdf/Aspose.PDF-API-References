---
title: System::Security::Cryptography::RSA::VerifyHash method
linktitle: VerifyHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::VerifyHash method. Verifies that the signature of the specified hash is valid in C++.'
type: docs
weight: 1400
url: /cpp/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash method


Verifies that the signature of the specified hash is valid.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash value of the signed data. |
| signature | ByteArrayPtr | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | SharedPtr\<RSASignaturePadding\> | Padding mode. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
