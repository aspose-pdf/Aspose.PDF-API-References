---
title: "System::IO::Stream::Write метод"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Stream::Write метод. Записывает указанный поддиапазон байтов из указанного массива байтов в поток в C++."
type: docs
weight: 2600
url: /ru/cpp/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива, содержащее байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Параметр | Описание |
| --- | --- |
| N | Размер стекового массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<uint8_t, N\>\& | Стековый массив, содержащий байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Записывает указанный поддиапазон байтов из указанного диапазона байтов в поток.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::ReadOnlySpan\<uint8_t\>\& | Диапазон байтов для чтения записанных байтов из |

## См. также

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
