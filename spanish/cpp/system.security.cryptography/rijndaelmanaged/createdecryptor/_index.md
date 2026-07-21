---
title: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor método"
linktitle: "CreateDecryptor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor método. Crea un objeto descifrador con los parámetros definidos por el objeto algoritmo en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor() method


Crea un objeto descifrador con parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Crea un objeto descifrador con parámetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Clave de cifrado en forma de matriz de bytes. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Valor inicial en forma de matriz de bytes. |

### ReturnValue

Objeto descifrador recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
