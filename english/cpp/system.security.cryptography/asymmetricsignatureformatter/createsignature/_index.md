---
title: System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature method
linktitle: CreateSignature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature method. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


RTTI information.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) to calculate hash for. |

### ReturnValue

Calculated signature in byte array form.
## Remarks


Creates the siguature for the specified data. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Creates the signature for the specified hash value.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hash | System::SharedPtr\<HashAlgorithm\> | Hash algorithm to use when creating signature. |

### ReturnValue

Calculated signature in byte array form.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
