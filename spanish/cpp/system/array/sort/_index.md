---
title: "Método System::Array::Sort"
linktitle: "Ordenar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Array::Sort. Ordena dos matrices, una que contiene claves y la otra los elementos correspondientes, basándose en los valores de la matriz que contiene claves, cuyos elementos se comparan usando operator< en C++."
type: docs
weight: 6000
url: /es/cpp/system/array/sort/
---
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Ordena dos arreglos, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del arreglo que contiene las claves, cuyos elementos se comparan usando operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de los elementos en la matriz **keys** |
| TValue | el tipo de los elementos en la matriz **items** |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) que contiene valores de clave |
| items | const ArrayPtr\<TValue\>\& | [Array](../) que contiene elementos que están mapeados a los valores de clave en la matriz **keys** |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Ordena dos arreglos, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del arreglo que contiene las claves, cuyos elementos se comparan usando el comparador predeterminado.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de los elementos en la matriz **keys** |
| TValue | el tipo de los elementos en la matriz **items** |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) que contiene valores de clave |
| items | const ArrayPtr\<TValue\>\& | [Array](../) que contiene elementos que están mapeados a los valores de clave en la matriz **keys** |
| índice | int | El índice que designa el inicio del rango a ordenar |
| longitud | int | El número de elementos en el rango a ordenar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&) method


Ordena los elementos del arreglo especificado usando el comparador predeterminado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Matriz objetivo |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Ordena los elementos del arreglo especificado usando el comparador especificado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Matriz objetivo |
| comparador | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Objeto IComparer<T> usado para comparar los elementos de la matriz |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


NO IMPLEMENTADO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method


Ordena los elementos del arreglo especificado usando la comparación especificada.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Comparison](../../comparison/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Ordena un rango de elementos del arreglo especificado usando el comparador predeterminado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Matriz objetivo |
| startIndex | int | El índice que designa el inicio del rango de elementos a ordenar |
| count | int | El tamaño del rango de elementos a ordenar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
