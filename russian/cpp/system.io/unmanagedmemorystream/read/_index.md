---
title: "Метод System::IO::UnmanagedMemoryStream::Read"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::UnmanagedMemoryStream::Read. Считывает указанное количество байтов из потока и записывает их в указанный массив байтов в C++."
type: docs
weight: 1000
url: /ru/cpp/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Считывает указанное количество байт из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив байтов, в который записываются считанные байты |
| смещение | int32_t | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int32_t | Количество байтов для чтения |

### ReturnValue

Количество считанных байтов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Считывает указанное количество байт из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива байтов, в которое записываются считанные байты |
| смещение | int32_t | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int32_t | Количество байтов для чтения |

### ReturnValue

Количество считанных байтов

## См. также

* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
