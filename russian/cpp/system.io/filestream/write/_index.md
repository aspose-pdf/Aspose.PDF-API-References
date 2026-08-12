---
title: "Метод System::IO::FileStream::Write"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::FileStream::Write. Записывает указанный поддиапазон байтов из заданного массива байтов в поток в C++."
type: docs
weight: 1900
url: /ru/cpp/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи. |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | int32_t | Количество элементов в поддиапазоне для записи. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива, содержащее байты для записи. |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | int32_t | Количество элементов в поддиапазоне для записи. |

## См. также

* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
