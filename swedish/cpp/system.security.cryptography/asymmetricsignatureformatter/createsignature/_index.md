---
title: "System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature-metoden"
linktitle: "CreateSignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature-metoden. RTTI-information i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


RTTI-information.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) för att beräkna hash för. |

### ReturnValue

Beräknad signatur i byte-array-format.
## Anmärkningar


Skapar signaturen för den angivna datan.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Skapar signaturen för det angivna hashvärdet.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | System::SharedPtr\<HashAlgorithm\> | Hash-algoritm att använda när signaturen skapas. |

### ReturnValue

Beräknad signatur i byte-array-format.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
