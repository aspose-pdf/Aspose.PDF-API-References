---
title: "System::Array::Array constructor"
linktitle: "Array"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::Array constructor. Construye un array vacío en C++."
type: docs
weight: 100
url: /es/cpp/system/array/array/
---
## Array::Array() constructor


Construye un array vacío.

```cpp
System::Array<T>::Array()
```

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor


Construye un objeto [Array](../) y lo llena con valores del array especificado que contiene elementos del tipo **[UnderlyingType](../underlyingtype/)**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


| Parámetro | Descripción |
| --- | --- |
| InitArraySize | Número de elementos del array **init**. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | const std::array\<UnderlyingType, InitArraySize\>\& | [Array](../) para copiar en el array que se está construyendo. |

## Ver también

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const std::vector\<Q\>\&) constructor


Construye un objeto [Array](../) y lo llena con valores copiados de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero diferente de **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


| Parámetro | Descripción |
| --- | --- |
| Q | El tipo de los elementos del objeto std::vector del que se copian los elementos. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | const std::vector\<Q\>\& | std::vector del cual copiar los valores |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(const vector_t\&) constructor


Constructor de copia.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assgn | const vector_t\& | std::vector del cual copiar valores |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T\&) constructor


Constructor de llenado.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | Tamaño inicial del array |
| init | const T\& | El valor inicial usado para llenar el array |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(int, const T) constructor


Constructor de llenado.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | Tamaño inicial del array |
| inicializaciones | const T | Valores con los que llenar el array |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<bool\>, int) constructor


Construye un objeto [Array](../) y lo llena con valores de la lista de inicialización especificada que contiene elementos del tipo bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | std::initializer_list\<bool\> | Lista de inicialización que contiene los elementos con los que llenar el array |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::initializer_list\<UnderlyingType\>) constructor


Construye un objeto [Array](../) y lo llena con valores de la lista de inicialización especificada que contiene elementos del tipo **[UnderlyingType](../underlyingtype/)**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| init | std::initializer_list\<UnderlyingType\> | Lista de inicialización que contiene los elementos con los que llenar el array |

## Ver también

* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(std::vector\<Q\>\&&) constructor


Construye un objeto [Array](../) y lo llena con valores movidos de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero diferente de **[UnderlyingType](../underlyingtype/)**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


| Parámetro | Descripción |
| --- | --- |
| Q | El tipo de los elementos del objeto std::vector del que mover los elementos. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | std::vector\<Q\>\&& | std::vector del cual copiar los valores |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor


Constructor de llenado.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


| Parámetro | Descripción |
| --- | --- |
| ValueType | Tipo del valor inicial |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type | Tamaño inicial del array |
| init | ValueType | El valor inicial usado para llenar el array |

## Ver también

* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Array(vector_t\&&) constructor


Constructor de movimiento.

```cpp
System::Array<T>::Array(vector_t &&value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | vector_t\&& | std::vector, elementos que son adquiridos por el arreglo |

## Ver también

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
