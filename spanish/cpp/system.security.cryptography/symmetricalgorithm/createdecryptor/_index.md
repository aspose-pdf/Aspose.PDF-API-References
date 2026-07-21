---
title: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor método"
linktitle: "CreateDecryptor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor método. Crea un descifrador con los parámetros asociados al objeto del algoritmo en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() method


Crea un descifrador con los parámetros asociados al objeto del algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### ReturnValue

Objeto descifrador recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Crea un descifrador con parámetros explícitos.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Clave a usar. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Valor inicial a usar. |

### ReturnValue

Objeto descifrador recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
