---
title: "System::Array::BinarySearch método"
linktitle: "BinarySearch"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::BinarySearch método. Realiza una búsqueda binaria en el arreglo ordenado en C++."
type: docs
weight: 4800
url: /es/cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Realiza una búsqueda binaria en el array ordenado.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | Arreglo ordenado en el que realizar la búsqueda |
| elemento | const T\& | Un elemento a buscar |

### ReturnValue

[Index](../../index/) of the searched item if one is found, otherwise, a negative integer that is the bitwise complement of the index of the next item greater than searched item or, if there is no greater item, the bitwise complement of the number of elements in the array.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


NO IMPLEMENTADO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
