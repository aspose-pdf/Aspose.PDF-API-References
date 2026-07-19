---
title: "System::IO::BufferedStream::Write метод"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BufferedStream::Write метод. Записывает указанный поддиапазон байтов из заданного массива байтов в базовый поток в C++."
type: docs
weight: 1400
url: /ru/cpp/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байтов из указанного массива байтов в базовый поток.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байтов из указанного массива байтов в базовый поток.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Массив, содержащий байты для записи |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
