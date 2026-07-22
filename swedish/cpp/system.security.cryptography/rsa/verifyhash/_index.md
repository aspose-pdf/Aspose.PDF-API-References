---
title: "System::Security::Cryptography::RSA::VerifyHash metod"
linktitle: "VerifyHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA::VerifyHash metod. Verifierar att signaturen för den angivna hashen är giltig i C++."
type: docs
weight: 1400
url: /sv/cpp/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash method


Verifierar att signaturen för den specificerade hash‑värdet är giltig.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
