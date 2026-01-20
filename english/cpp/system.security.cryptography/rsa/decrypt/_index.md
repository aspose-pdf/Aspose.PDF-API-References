---
title: System::Security::Cryptography::RSA::Decrypt method
linktitle: Decrypt
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::Decrypt method. Decrypts input data using the specified padding mode in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt method


Decrypts input data using the specified padding mode.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) array to decrypt. |
| padding | SharedPtr\<RSAEncryptionPadding\> | Padding mode. |

### ReturnValue

Decrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
