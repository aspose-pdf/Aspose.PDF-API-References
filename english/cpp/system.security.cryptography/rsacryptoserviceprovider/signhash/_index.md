---
title: System::Security::Cryptography::RSACryptoServiceProvider::SignHash method
linktitle: SignHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSACryptoServiceProvider::SignHash method. Computes the signature for the specified hash value in C++.'
type: docs
weight: 1700
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method


Computes the signature for the specified hash value.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash value. |
| hash_algorithm | HashAlgorithmName | Hash algorithm. |
| padding | SharedPtr\<RSASignaturePadding\> | Padding mode. return [RSA](../../rsa/) signature for the specified hash. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method


Computes the signature of specified input value. Not implemented.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hash value of data to be signed. |
| str | const String\& | Hash algorithm identifier used to create the hash. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
