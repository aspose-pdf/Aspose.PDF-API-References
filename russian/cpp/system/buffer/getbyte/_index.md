---
title: "System::Buffer::GetByte метод"
linktitle: "GetByte"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Buffer::GetByte метод. Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по указанному смещению в C++."
type: docs
weight: 300
url: /ru/cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const SharedPtr\<Array\<T\>\>\& | Целевой массив |
| индекс | int | Смещение байта, которое нужно получить, начиная с нуля |

### ReturnValue

Значение байта по указанному индексу

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов представления массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::ArrayView\<T\>\& | Целевое представление массива |
| индекс | int | Смещение байта, которое нужно получить, начиная с нуля |

### ReturnValue

Значение байта по указанному индексу

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и получает значение байта по указанному смещению.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов стекового массива |
| N | Размер стекового массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::StackArray\<T, N\>\& | Целевой стековый массив |
| индекс | int | Смещение байта, которое нужно получить, начиная с нуля |

### ReturnValue

Значение байта по указанному индексу

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
