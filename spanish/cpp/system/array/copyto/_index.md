---
title: "Método System::Array::CopyTo"
linktitle: "CopyTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Array::CopyTo. Copia todos los elementos del arreglo actual al arreglo de destino especificado. Los elementos se insertan en el arreglo de destino comenzando en el índice especificado por el argumento arrayIndex en C++."
type: docs
weight: 900
url: /es/cpp/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) method


Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Arreglo de destino |
| arrayIndex | int | [Index](../../index/) en el arreglo de destino para comenzar a insertar los elementos copiados |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const method


Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Arreglo de destino |
| dstIndex | int64_t | [Index](../../index/) en el arreglo de destino para comenzar a insertar los elementos copiados |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const ArrayPtr\<DstType\>\& | Arreglo de destino |
| srcIndex | int64_t | [Index](../../index/) en el arreglo de origen para comenzar a copiar los elementos |
| dstIndex | int64_t | [Index](../../index/) en el arreglo de destino para comenzar a insertar los elementos copiados |
| count | int64_t | Número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const method


Copia todos los elementos del array actual a la vista del array de destino especificada. Los elementos se insertan en la vista del array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista del arreglo de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista del arreglo de destino |
| dstIndex | int64_t | [Index](../../index/) en la vista del arreglo de destino para comenzar a insertar los elementos copiados |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const method


Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada a la vista del array de destino especificada. Los elementos se insertan en la vista del array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista del arreglo de destino |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista del arreglo de destino |
| srcIndex | int64_t | [Index](../../index/) en el arreglo de origen para comenzar a copiar los elementos |
| dstIndex | int64_t | [Index](../../index/) en la vista del arreglo de destino para comenzar a insertar los elementos copiados |
| count | int64_t | Número de elementos a copiar |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
