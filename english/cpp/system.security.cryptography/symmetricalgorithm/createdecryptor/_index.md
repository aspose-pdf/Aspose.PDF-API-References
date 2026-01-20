---
title: System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor method
linktitle: CreateDecryptor
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor method. Creates decryptor with parameters associated with algorithm object in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() method


Creates decryptor with parameters associated with algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### ReturnValue

Newly created decryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Creates decryptor with explicit parameters.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Key to use. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initial value to use. |

### ReturnValue

Newly created decryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
