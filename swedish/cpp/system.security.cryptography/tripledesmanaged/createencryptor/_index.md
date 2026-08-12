---
title: "System::Security::Cryptography::TripleDESManaged::CreateEncryptor metod"
linktitle: "CreateEncryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::TripleDESManaged::CreateEncryptor metod. Skapar ett krypteringsobjekt med parametrar som definieras av algoritmobjektet i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor() method


Skapar krypteringsobjekt med parametrar som definieras av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar krypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Krypteringsnyckel i bytearray-form. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initialvärde i bytearray-form. |

### ReturnValue

Nyligen skapat krypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
