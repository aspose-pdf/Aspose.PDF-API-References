---
title: "Método System::BuildArray"
linktitle: "BuildArray"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::BuildArray. Construye una matriz en C++."
type: docs
weight: 15600
url: /es/cpp/system/buildarray/
---
## System::BuildArray method


Construye una matriz.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento del arreglo a construir |

### ReturnValue

ObjectBuilder configurado para la construcción de arreglos
## Observaciones



Crea un [ArrayPtr<T>](../arrayptr/) y devuelve un constructor para él
[Object](../object/) construction must be finished with [Get()](../get/) call 

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
