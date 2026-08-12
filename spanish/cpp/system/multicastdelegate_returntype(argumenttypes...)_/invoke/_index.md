---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke método"
linktitle: "invoke"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke método. Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron añadidos a la colección. El método bloquea mientras los delegados se ejecutan en C++."
type: docs
weight: 1200
url: /es/cpp/system/multicastdelegate_returntype(argumenttypes...)_/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke method


Invoca todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El método se bloquea mientras se ejecutan los delegados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
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
