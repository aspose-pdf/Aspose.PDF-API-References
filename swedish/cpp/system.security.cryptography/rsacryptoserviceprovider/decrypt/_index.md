---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt metod"
linktitle: "Dekryptera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt metod. Avkrypterar indata med angivet utfyllnadsläge i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Dekrypterar indata med den specificerade utfyllnadsläget.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) array att dekryptera. |
| utfyllnad | SharedPtr\<RSAEncryptionPadding\> | Utfyllnadsläge. |

### ReturnValue

Dekrypterad data i bytearrayformat.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Dekrypterar meddelande. Ej implementerad.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) för att dekryptera. |
| use_oaep | bool | Sant för att använda OAEP-padding, falskt för att använda PKCS#1 v1.5-padding. |

### ReturnValue

Dekrypterad dataarray.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
