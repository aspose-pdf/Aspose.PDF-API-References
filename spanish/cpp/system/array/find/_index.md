---
title: "Método System::Array::Find"
linktitle: "Find"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Array::Find. Busca el primer elemento en el arreglo especificado que cumple las condiciones del predicado especificado en C++."
type: docs
weight: 5300
url: /es/cpp/system/array/find/
---
## Array::Find method


Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) para buscar un elemento en |
| coincidir | System::Predicate\<T\> | Un predicado que define las condiciones contra las que comparar los elementos del arreglo |

### ReturnValue

Copia del primer elemento del arreglo que cumple las condiciones definidas por el predicado; de lo contrario, el valor predeterminado del tipo T

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
