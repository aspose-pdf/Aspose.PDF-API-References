---
title: "Метод System::Array::LastIndexOf"
linktitle: "LastIndexOf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::LastIndexOf. Определяет индекс последнего вхождения указанного элемента в диапазоне элементов массива, заданном начальным индексом и количеством элементов в диапазоне, в C++."
type: docs
weight: 5700
url: /ru/cpp/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Определяет индекс последнего вхождения указанного элемента в диапазоне элементов массива, заданном стартовым индексом и количеством элементов в диапазоне.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента для поиска в массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const ValueType\& | Индекс элемента, который нужно определить |
| startIndex | int | [Index](../../index/) с которого начинается поиск |
| count | int | Количество элементов диапазона для поиска |

### ReturnValue

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Определяет индекс последнего вхождения указанного элемента в массив.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента для поиска в массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const ValueType\& | Индекс элемента, который нужно определить |

### ReturnValue

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Определяет индекс последнего вхождения указанного элемента в массив, начиная с указанного индекса.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента для поиска в массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const ValueType\& | Индекс элемента, который нужно определить |
| startIndex | int | [Index](../../index/) с которого начинается поиск |

### ReturnValue

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
