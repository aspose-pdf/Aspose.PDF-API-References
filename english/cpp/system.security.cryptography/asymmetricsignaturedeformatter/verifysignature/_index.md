---
title: System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method
linktitle: VerifySignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method. Verifies signature on data in C++.'
type: docs
weight: 300
url: /cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Verifies signature on data.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) signed with **rgbSignature**. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signature to be verified for data. |

### ReturnValue

True if signature check succeeds, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Verifies signature on data. Not implemented.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | System::SharedPtr\<HashAlgorithm\> | Algorithm to use for hashing. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signature to be verified for data. |

### ReturnValue

True if signature check succeeds, false otherwise.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
