---
title: "System::Buffer::SetByte метод"
linktitle: "SetByte"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Buffer::SetByte метод. Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает указанное значение байта по заданному смещению байта в C++."
type: docs
weight: 400
url: /ru/cpp/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const SharedPtr\<Array\<T\>\>\& | Целевой массив |
| индекс | int | Смещение байта, начиная с нуля, которое нужно установить |
| value | uint8_t | Значение байта для установки |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::ArrayView\<T\>\& | Целевое представление массива |
| индекс | int | Смещение байта, начиная с нуля, которое нужно установить |
| value | uint8_t | Значение байта для установки |

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method


Интерпретирует указанный типизированный массив как необработанный массив байтов и устанавливает указанное значение байта по указанному смещению.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |
| N | Размер стекового массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::StackArray\<T, N\>\& | Целевой стековый массив |
| индекс | int | Смещение байта, начиная с нуля, которое нужно установить |
| value | uint8_t | Значение байта для установки |

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
