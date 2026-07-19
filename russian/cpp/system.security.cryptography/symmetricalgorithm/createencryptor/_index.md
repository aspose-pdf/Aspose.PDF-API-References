---
title: "System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor метод"
linktitle: "CreateEncryptor"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor метод. Создаёт шифратор с параметрами, связанными с объектом алгоритма, в C++."
type: docs
weight: 200
url: /ru/cpp/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() method


Создаёт шифратор с параметрами, связанными с объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```


### ReturnValue

Недавно созданный объект шифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Создаёт шифратор с явными параметрами.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Ключ для использования. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Исходное значение для использования. |

### ReturnValue

Недавно созданный объект шифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
