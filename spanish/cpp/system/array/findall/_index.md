---
title: "System::Array::FindAll método"
linktitle: "FindAll"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::FindAll método. Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado en C++."
type: docs
weight: 5400
url: /es/cpp/system/array/findall/
---
## Array::FindAll method


Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) para buscar elementos en |
| coincidir | System::Predicate\<T\> | Un predicado que define las condiciones contra las que comparar los elementos del arreglo |

### ReturnValue

Un [Array](../) que contiene todos los elementos que coinciden con las condiciones definidas por el predicado especificado, si se encuentran; de lo contrario, un [Array](../) vacío.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
