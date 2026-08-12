---
title: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor metod"
linktitle: "CreateDecryptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor metod. Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor() method


Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Skapar avkrypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
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
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
