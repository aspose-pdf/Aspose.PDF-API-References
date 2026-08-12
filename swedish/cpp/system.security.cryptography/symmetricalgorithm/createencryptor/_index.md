---
title: "System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor metod"
linktitle: "CreateEncryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor metod. Skapar en krypterare med parametrar som är associerade med algoritmobjektet i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() method


Skapar krypterare med parametrar som är associerade med algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```


### ReturnValue

Nyligen skapat krypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar krypterare med explicita parametrar.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Nyckel att använda. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initialt värde att använda. |

### ReturnValue

Nyligen skapat krypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
