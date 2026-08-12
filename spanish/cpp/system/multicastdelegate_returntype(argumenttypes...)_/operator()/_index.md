---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() método"
linktitle: "operator()"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() método. Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El operador se bloquea mientras los delegados se ejecutan en C++."
type: docs
weight: 1500
url: /es/cpp/system/multicastdelegate_returntype(argumenttypes...)_/operator()/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method


Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron añadidos a la colección. El operador se bloquea mientras se ejecutan los delegados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | ArgumentTypes... | Argumentos a pasar a los delegados que serán invocados |

### ReturnValue

Valor de retorno del último delegado invocado

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
