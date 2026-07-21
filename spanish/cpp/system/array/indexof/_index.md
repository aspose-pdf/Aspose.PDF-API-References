---
title: "Método System::Array::IndexOf"
linktitle: "IndexOf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Array::IndexOf. Determina el índice de la primera aparición del elemento especificado en el arreglo en C++."
type: docs
weight: 2900
url: /es/cpp/system/array/indexof/
---
## Array::IndexOf(const T\&) const method


Determina el índice de la primera aparición del elemento especificado en la matriz.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | const T\& | Índice del elemento que se debe determinar |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Determina el índice de la primera aparición del elemento especificado en la matriz.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo objetivo |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |

### ReturnValue

[Index](../../index/) of the first occurrence specified item if the item is found, otherwise -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Determina el índice de la primera aparición del elemento especificado en la matriz a partir del índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo objetivo |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Determina el índice de la primera aparición del elemento especificado en un rango de elementos de la matriz especificado por el índice de inicio y el número de elementos en el rango.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo objetivo |
| ValueType | tipo del elemento a buscar en el array |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| valor | const ValueType\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |
| count | int | Número de elementos del rango en el que buscar |

### ReturnValue

[Index](../../index/) of the first occurrence of the specified item if the item is found, otherwise -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
