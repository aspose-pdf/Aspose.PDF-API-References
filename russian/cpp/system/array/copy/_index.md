---
title: "System::Array::Copy метод"
linktitle: "Copy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Array::Copy метод. Копирует указанное количество элементов из исходного массива в массив назначения в C++."
type: docs
weight: 5100
url: /ru/cpp/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Копирует указанное количество элементов из исходного массива в массив‑назначение.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию массива‑назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в целевом массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве, обозначающий начало диапазона копируемых элементов |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| dstIndex | int64_t | [Index](../../index/) в целевом массиве, указывающий место начала вставки скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию представления массива‑назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в представлении целевого массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве, обозначающий начало диапазона копируемых элементов |
| dstArray | System::Details::ArrayView\<DstType\> | Представление массива назначения |
| dstIndex | int64_t | [Index](../../index/) в представлении массива назначения, с которого начинать вставку скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию целевого массива в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в массиве назначения в стеке |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве, обозначающий начало диапазона копируемых элементов |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Массив назначения в стеке |
| dstIndex | int64_t | [Index](../../index/) в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method


Копирует указанное количество элементов из исходного массива в представление массива‑назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| dstArray | System::Details::ArrayView\<DstType\> | Представление массива назначения |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method


Копирует указанное количество элементов из исходного массива в массив‑назначение в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Исходный массив |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Массив назначения в стеке |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию целевого массива в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве в стеке |
| DstType | Тип элементов в массиве назначения в стеке |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Представление исходного массива |
| srcIndex | int64_t | [Index](../../index/) в представлении исходного массива, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| dstIndex | int64_t | [Index](../../index/) в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method


Копирует указанное количество элементов из представления исходного массива в массив‑назначение.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Представление исходного массива |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию массива‑назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в представлении исходного массива |
| DstType | Тип элементов в целевом массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Представление исходного массива |
| srcIndex | int64_t | [Index](../../index/) в представлении исходного массива, обозначающий начало диапазона элементов для копирования |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| dstIndex | int64_t | [Index](../../index/) в целевом массиве, указывающий место начала вставки скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method


Копирует указанное количество элементов из представления исходного массива, начиная с указанного индекса, в указанную позицию представления целевого массива.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в представлении исходного массива |
| DstType | Тип элементов в представлении целевого массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Представление исходного массива |
| srcIndex | int64_t | [Index](../../index/) в представлении исходного массива, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::ArrayView\<DstType\> | Представление массива назначения |
| dstIndex | int64_t | [Index](../../index/) в представлении массива назначения, с которого начинать вставку скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method


Копирует указанное количество элементов из представления исходного массива в представление массива‑назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Представление исходного массива |
| dstArray | System::Details::ArrayView\<DstType\> | Представление массива назначения |
| count | int64_t | Количество элементов для копирования |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method


Копирует указанное количество элементов из массива‑источника в стеке в массив‑назначение.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Исходный массив в стеке |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию целевого массива.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве в стеке |
| DstType | Тип элементов в целевом массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Исходный массив в стеке |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве в стеке, обозначающий начало диапазона элементов для копирования |
| dstArray | const ArrayPtr\<DstType\>\& | Целевой массив |
| dstIndex | int64_t | [Index](../../index/) в целевом массиве, указывающий место начала вставки скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method


Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию целевого массива в стеке.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве в стеке |
| DstType | Тип элементов в массиве назначения в стеке |

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Исходный массив в стеке |
| srcIndex | int64_t | [Index](../../index/) в исходном массиве в стеке, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| dstIndex | int64_t | [Index](../../index/) в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | int64_t | Количество элементов для копирования |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method


Копирует указанное количество элементов из массива‑источника в стеке в массив‑назначение в стеке.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Исходный массив в стеке |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| count | int64_t | Количество элементов для копирования |

## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
