---
title: "Método System::InitObject."
linktitle: "InicializarObjeto"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::InitObject. Inicia la inicialización de un objeto con propiedad compartida en C++."
type: docs
weight: 22500
url: /es/cpp/system/initobject/
---
## System::InitObject method


Inicia la inicialización de un objeto con propiedad compartida.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a inicializar |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const SharedPtr\<T\>\& | [Object](../object/) a inicializar |

### ReturnValue

ObjectBuilder configurado para la construcción de punteros compartidos
## Observaciones



[Object](../object/) initialization must be finished with [Get()](../get/) call 

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
