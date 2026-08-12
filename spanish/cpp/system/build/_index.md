---
title: "Método System::Build"
linktitle: "Build"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Build. Construye un objeto con propiedad directa en C++."
type: docs
weight: 15500
url: /es/cpp/system/build/
---
## System::Build method


Construye un objeto con propiedad directa.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a construir |
| Args | Tipos de argumentos para la construcción del objeto |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos para reenviar al constructor del objeto |

### ReturnValue

ObjectBuilder configurado para construcción directa de objetos
## Observaciones



[Object](../object/) construction must be finished with [Get()](../get/) call 

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
