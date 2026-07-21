---
title: "Método System::Get"
linktitle: "Obtener"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Get. Función para obtener el N-ésimo elemento de una tupla dada. Sobrecarga para objeto base en C++."
type: docs
weight: 21200
url: /es/cpp/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) method


Función para obtener el N-ésimo elemento de una tupla dada. Sobrecarga para objeto base.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objeto | const SharedPtr\<Object\>\& | objeto a inspeccionar. |

### ReturnValue

valor del elemento N-ésimo de la tupla convertido a objeto.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const SharedPtr\<T\>\&) method


Función para obtener el N-ésimo elemento de una tupla dada. Sobrecarga para punteros compartidos.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| T | tipo del objeto inspeccionado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objeto | const SharedPtr\<T\>\& | objeto a inspeccionar. |

### ReturnValue

valor del elemento N-ésimo de la tupla.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const T\&) method


Función para obtener el N-ésimo elemento de una tupla dada. Sobrecarga para objetos con método Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| T | tipo del objeto inspeccionado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objeto | const T\& | objeto a inspeccionar. |

### ReturnValue

valor del elemento N-ésimo de la tupla.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const ValueTuple\<Args...\>\&) method


Obtiene el N-ésimo elemento de una tupla de valores.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| Args | elementos de la tupla. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tupla | const ValueTuple\<Args...\>\& | tupla de la cual obtener el elemento. |

### ReturnValue

valor del elemento N-ésimo de la tupla.

## Ver también

* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Index\&) method


Implementación para expresiones collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de colección. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colección | T\& | Objeto de colección. |
| index | const Index\& | Índice del elemento de tipo [System.Index](../index/). |

### ReturnValue

Elemento de la colección en el desplazamiento calculado.

## Ver también

* Class [Index](../index/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Range\&) method


Devuelve una porción de la colección especificada definida por el rango proporcionado.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colección | T\& | La colección a segmentar. |
| rango | const Range\& | El rango que especifica los límites de la porción. |

### ReturnValue

Una vista o porción de la colección desde el desplazamiento inicial calculado y la longitud.

## Ver también

* Class [Range](../range/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
