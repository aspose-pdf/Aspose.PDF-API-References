---
title: "System::IO::BasicSTDIStreamWrapper::Write метод"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::BasicSTDIStreamWrapper::Write. Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип char_type и затем записывает результат в поток. Не поддерживается! в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Если режим обёртывания бинарный, записывает в поток указанный поддиапазон байтов из указанного массива байтов, иначе преобразует указанный поддиапазон байтов из указанного массива байтов в тип [char_type](../char_type/) и затем записывает результат в поток. Не поддерживается!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи. |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | int32_t | Количество элементов в поддиапазоне для записи. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива, содержащее байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
