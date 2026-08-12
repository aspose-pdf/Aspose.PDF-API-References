---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method"
linktitle: "Kryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method. Krypterar indata med det angivna paddningsläget i C++."
type: docs
weight: 400
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Krypterar indata med den specificerade utfyllnadsläget.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
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
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Krypterar meddelande. Ej implementerad.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) för att kryptera. |
| use_oaep | bool | Sant för att använda OAEP-padding, falskt för att använda PKCS#1 v1.5-padding. |

### ReturnValue

Krypterad dataarray.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
