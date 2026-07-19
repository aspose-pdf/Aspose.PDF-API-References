---
title: "System::Net::Sockets::NetworkStream::Write метод"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream::Write метод. Записывает указанный поддиапазон байтов из указанного массива байтов в поток в C++."
type: docs
weight: 2500
url: /ru/cpp/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи. |
| смещение | int32_t | Смещение в байтах в указанном массиве. |
| size | int32_t | Количество элементов в поддиапазоне для записи. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Записывает указанный поддиапазон байт из указанного массива байтов в поток.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | Представление массива, содержащее байты для записи |
| смещение | int32_t | Индекс, начинающийся с 0, элемента в **buffer**, с которого начинается поддиапазон для записи |
| size | int32_t | Количество элементов в поддиапазоне для записи |

## См. также

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
