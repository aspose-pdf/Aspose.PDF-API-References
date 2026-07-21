---
title: "Método System::Collections::Generic::_net_binnary_search"
linktitle: "_net_binnary_search"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Collections::Generic::_net_binnary_search. Implementa búsqueda binaria en un contenedor de acceso aleatorio. Especialización para punteros inteligentes. Utiliza el método System::Object::CompareTo en C++."
type: docs
weight: 4900
url: /es/cpp/system.collections.generic/_net_binnary_search/
---
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementa búsqueda binaria en un contenedor de acceso aleatorio. Especialización para punteros inteligentes. Utiliza el método System::Object::CompareTo.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<IsSmartPtr<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parámetro | Descripción |
| --- | --- |
| containerT | Tipo de plantilla de contenedor con estilo STL con dos argumentos de plantilla: tipo de elemento y tipo de asignador. |
| T | Tipo de elemento. |
| Asignador | Tipo de asignador. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenedor | const containterT\<T, Allocator\>\& | Contenedor en el que buscar. |
| índice | int | Índice inicial del rango de búsqueda. |
| count | int | Longitud del rango de búsqueda. |
| valor | T | Valor a buscar. |

### ReturnValue

Si se encuentra, índice del siguiente elemento; de lo contrario, complementos del índice donde se detuvo la búsqueda.

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementa búsqueda binaria en un contenedor de acceso aleatorio. Especialización para tipos de valor. Utiliza el método CompareTo.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parámetro | Descripción |
| --- | --- |
| containerT | Tipo de plantilla de contenedor con estilo STL con dos argumentos de plantilla: tipo de elemento y tipo de asignador. |
| T | Tipo de elemento. |
| Asignador | Tipo de asignador. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenedor | const containterT\<T, Allocator\>\& | Contenedor en el que buscar. |
| índice | int | Índice inicial del rango de búsqueda. |
| count | int | Longitud del rango de búsqueda. |
| valor | T | Valor a buscar. |

### ReturnValue

Si se encuentra, índice del siguiente elemento; de lo contrario, complementos del índice donde se detuvo la búsqueda.

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Implementa búsqueda binaria en un contenedor de acceso aleatorio. Especialización para tipos escalares. Compara los elementos usando los operadores mayor que y menor que.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Parámetro | Descripción |
| --- | --- |
| containerT | Tipo de plantilla de contenedor con estilo STL con dos argumentos de plantilla: tipo de elemento y tipo de asignador. |
| T | Tipo de elemento. |
| Asignador | Tipo de asignador. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenedor | const containterT\<T, Allocator\>\& | Contenedor en el que buscar. |
| índice | int | Índice inicial del rango de búsqueda. |
| count | int | Longitud del rango de búsqueda. |
| valor | T | Valor a buscar. |

### ReturnValue

Si se encuentra, índice del siguiente elemento; de lo contrario, complementos del índice donde se detuvo la búsqueda.

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Implementa búsqueda binaria en un contenedor de acceso aleatorio.

```cpp
template<template< typename, typename > class,class T,class Allocator> int System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer)
```


| Parámetro | Descripción |
| --- | --- |
| containerT | Tipo de plantilla de contenedor con estilo STL con dos argumentos de plantilla: tipo de elemento y tipo de asignador. |
| T | Tipo de elemento. |
| Asignador | Tipo de asignador. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenedor | const containterT\<T, Allocator\>\& | Contenedor en el que buscar. |
| índice | int | Índice inicial del rango de búsqueda. |
| count | int | Longitud del rango de búsqueda. |
| valor | T | Valor a buscar. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../comparer/) objeto. |

### ReturnValue

Si se encuentra, índice del siguiente elemento; de lo contrario, complementos del índice donde se detuvo la búsqueda.

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
