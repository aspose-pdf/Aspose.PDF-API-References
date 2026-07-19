---
title: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor метод"
linktitle: "CreateDecryptor"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor метод. Создаёт дешифратор с параметрами, связанными с объектом алгоритма, в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() method


Создаёт дешифратор с параметрами, связанными с объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### ReturnValue

Новый созданный объект дешифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Создаёт дешифратор с явными параметрами.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Ключ для использования. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Исходное значение для использования. |

### ReturnValue

Новый созданный объект дешифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
