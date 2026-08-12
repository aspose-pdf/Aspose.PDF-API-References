---
title: "System::Array::FindIndex method"
linktitle: "FindIndex"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::FindIndex method. Busca el primer elemento en el array especificado que satisface las condiciones del predicado especificado en C++."
type: docs
weight: 5500
url: /es/cpp/system/array/findindex/
---
## Array::FindIndex method


Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) para buscar un elemento en |
| coincidir | System::Predicate\<T\> | Un predicado que define las condiciones contra las que comparar los elementos del arreglo |

### ReturnValue

El índice del primer elemento del array que satisface las condiciones definidas por el predicado, de lo contrario -1.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
