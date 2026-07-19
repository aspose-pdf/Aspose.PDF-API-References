---
title: "Метод System::IO::BasicSTDOStreamWrapper::Read"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSTDOStreamWrapper::Read метод. Если режим обёртывания бинарный, читает указанное количество байтов из потока, иначе читает указанное количество символов и преобразует их в тип uint8_t. Записывает результат чтения в указанный массив байтов. Не поддерживается! в C++."
type: docs
weight: 400
url: /ru/cpp/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Если режим обёртки бинарный, читает указанное количество байтов из потока, иначе читает указанное количество символов и преобразует их в тип uint8_t. Записывает результат чтения в указанный массив байтов. Не поддерживается!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив байтов, в который записываются считанные байты |
| смещение | int32_t | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int32_t | Количество байтов для чтения |

### ReturnValue

Количество прочитанных байтов или символов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Считывает указанное количество байт из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива байтов, в которое записываются считанные байты |
| смещение | int32_t | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int32_t | Количество байтов для чтения |

### ReturnValue

Количество считанных байтов

## См. также

* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
