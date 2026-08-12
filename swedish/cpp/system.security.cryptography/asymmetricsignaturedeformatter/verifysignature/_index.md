---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method"
linktitle: "VerifySignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method. Verifierar signatur på data i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Verifierar signatur på data.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) signerad med **rgbSignature**. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signatur att verifieras för data. |

### ReturnValue

Sant om signaturkontrollen lyckas, falskt annars.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Verifierar signatur på data. Ej implementerad.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | System::SharedPtr\<HashAlgorithm\> | Algoritm att använda för hashning. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signatur att verifieras för data. |

### ReturnValue

Sant om signaturkontrollen lyckas, falskt annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
