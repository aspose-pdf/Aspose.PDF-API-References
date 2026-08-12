---
title: "System::Security::Cryptography::TripleDESManaged::CreateDecryptor metod"
linktitle: "CreateDecryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::TripleDESManaged::CreateDecryptor metod. Skapar ett dekrypteringsobjekt med parametrar definierade av algoritmobjektet i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor() method


Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar avkrypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Krypteringsnyckel i bytearray-form. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initialvärde i bytearray-form. |

### ReturnValue

Nyskapat dekrypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
