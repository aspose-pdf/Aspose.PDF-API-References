---
title: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor метод"
linktitle: "CreateDecryptor"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RijndaelManaged::CreateDecryptor метод. Создаёт объект дешифратора с параметрами, определёнными объектом алгоритма в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor() method


Создаёт объект дешифратора с параметрами, определёнными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Создаёт объект дешифратора с явными параметрами.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Ключ шифрования в виде массива байтов. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Начальное значение в виде массива байтов. |

### ReturnValue

Новый созданный объект дешифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
