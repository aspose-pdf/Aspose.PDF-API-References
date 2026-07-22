---
title: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash method"
linktitle: "VerifyHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash method. Verifierar att signaturen för den angivna hash‑värdet är giltig i C++."
type: docs
weight: 1900
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Verifierar att signaturen för den specificerade hash‑värdet är giltig.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | ByteArrayPtr | Hashvärde för den signerade datan. |
| signatur | ByteArrayPtr | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| utfyllnad | SharedPtr\<RSASignaturePadding\> | Paddingläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hash beräknad för mottagen data. |
| str | const String\& | Namn på hash-algoritm som används. |
| rgb_signature | const ByteArrayPtr\& | Signatur som mottogs. |

### ReturnValue

Sant om signaturen är giltig, falskt annars.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
