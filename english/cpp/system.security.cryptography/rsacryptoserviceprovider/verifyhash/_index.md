---
title: System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash method
linktitle: VerifyHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash method. Verifies that the signature of the specified hash is valid in C++.'
type: docs
weight: 1900
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Verifies that the signature of the specified hash is valid.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
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
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Checks data signature.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
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
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
