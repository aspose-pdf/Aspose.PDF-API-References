---
title: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor‑metod"
linktitle: "CreateDecryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor‑metod. Skapar en dekrypterare med parametrar som är associerade med algoritmobjektet i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() method


Skapar avkrypterare med parametrar som är associerade med algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### ReturnValue

Nyskapat dekrypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar avkrypterare med explicita parametrar.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Nyckel att använda. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initialt värde att använda. |

### ReturnValue

Nyskapat dekrypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
