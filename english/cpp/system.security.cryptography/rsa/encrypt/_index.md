---
title: System::Security::Cryptography::RSA::Encrypt method
linktitle: Encrypt
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::Encrypt method. Encrypts input data using the specified padding mode in C++.'
type: docs
weight: 300
url: /cpp/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt method


Encrypts input data using the specified padding mode.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
