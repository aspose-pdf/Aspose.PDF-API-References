---
title: "System::Security::Cryptography::RC2Managed::CreateEncryptor metod"
linktitle: "CreateEncryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RC2Managed::CreateEncryptor metod. Skapar ett krypteringsobjekt med parametrar som definieras av algoritmobjektet i C++."
type: docs
weight: 200
url: /sv/cpp/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor() method


Skapar krypteringsobjekt med parametrar som definieras av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar krypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
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
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
