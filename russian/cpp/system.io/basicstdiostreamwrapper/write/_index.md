---
title: "System::IO::BasicSTDIOStreamWrapper::Write метод"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSTDIOStreamWrapper::Write метод. Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип char_type и затем записывает результат в поток в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Если режим обёртки бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип [char_type](../char_type/) и затем записывает результат в поток.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи |
| смещение | int32_t | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива, содержащее байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
