---
title: "System::Security::Cryptography::RSA::Encrypt metod"
linktitle: "Kryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA::Encrypt metod. Krypterar indata med det angivna utfyllnadsläget i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt method


Krypterar indata med den specificerade utfyllnadsläget.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) array att kryptera. |
| utfyllnad | SharedPtr\<RSAEncryptionPadding\> | Utfyllnadsläge. |

### ReturnValue

Krypterad data i bytearrayformat.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
