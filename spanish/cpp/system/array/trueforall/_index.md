---
title: "System::Array::TrueForAll method"
linktitle: "TrueForAll"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::TrueForAll method. Determina si todos los elementos en el array especificado cumplen las condiciones definidas por el predicado especificado en C++."
type: docs
weight: 6100
url: /es/cpp/system/array/trueforall/
---
## Array::TrueForAll method


Determina si todos los elementos del arreglo especificado cumplen las condiciones definidas por el predicado especificado.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) elementos contra los que comparar las condiciones |
| coincidir | System::Predicate\<T\> | Un predicado que define las condiciones contra las que comparar los elementos del arreglo |

### ReturnValue

true si todos los elementos del array arr cumplen las condiciones definidas por el predicado match, de lo contrario false

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
