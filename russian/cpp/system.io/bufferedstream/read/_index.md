---
title: "System::IO::BufferedStream::Read метод"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BufferedStream::Read метод. Считывает указанное количество байтов из базового потока и записывает их в заданный массив байтов в C++."
type: docs
weight: 900
url: /ru/cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
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
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Массив байтов, в который записываются считанные байты |
| смещение | int32_t | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int32_t | Количество байтов для чтения |

### ReturnValue

Количество считанных байтов

## См. также

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
