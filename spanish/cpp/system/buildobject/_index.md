---
title: "System::BuildObject método"
linktitle: "BuildObject"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::BuildObject método. Construye un objeto con propiedad compartida en C++."
type: docs
weight: 15700
url: /es/cpp/system/buildobject/
---
## System::BuildObject method


Construye un objeto con propiedad compartida.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a construir |
| Args | Tipos de argumentos para la construcción del objeto |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos para reenviar al constructor del objeto |

### ReturnValue

ObjectBuilder configurado para la construcción de punteros compartidos
## Observaciones



Crea un [SharedPtr<T>](../sharedptr/) y devuelve un constructor para él
[Object](../object/) construction must be finished with [Get()](../get/) call 

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
