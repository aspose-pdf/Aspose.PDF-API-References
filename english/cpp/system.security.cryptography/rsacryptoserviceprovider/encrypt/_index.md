---
title: System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method. Encrypts input data using the specified padding mode in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Encrypts input data using the specified padding mode.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) array to encrypt. |
| padding | SharedPtr\<RSAEncryptionPadding\> | Padding mode. |

### ReturnValue

Encrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Encrypts message. Not implemented.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) to encrypt. |
| use_oaep | bool | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### ReturnValue

Encrypted data array.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
