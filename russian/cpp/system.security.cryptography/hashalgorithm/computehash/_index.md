---
title: "System::Security::Cryptography::HashAlgorithm::ComputeHash method"
linktitle: "ComputeHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::HashAlgorithm::ComputeHash method. Вычисляет хеш буфера в C++."
type: docs
weight: 200
url: /ru/cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method


Хеширует буфер.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Исходный буфер. |

### ReturnValue

Вычисленное значение хеша.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method


Хеширует часть буфера.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Исходный буфер. |
| смещение | int | Смещение в исходном буфере. |
| count | int | Количество байтов, используемых из исходного буфера. |

### ReturnValue

Вычисленное значение хеша.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method


Читает поток до конца и вычисляет хеш прочитанных данных.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | SharedPtr\<IO::Stream\> const\& | Поток для чтения данных. |

### ReturnValue

Вычисленное значение хеша для всех данных потока.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
