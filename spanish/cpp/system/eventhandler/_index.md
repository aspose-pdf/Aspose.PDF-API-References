---
title: "System::EventHandler typedef"
linktitle: "EventHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::EventHandler typedef. Representa un método que reacciona y procesa un evento. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 11800
url: /es/cpp/system/eventhandler/
---
## EventHandler typedef


Representa un método que reacciona y procesa un evento. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
using System::EventHandler =  MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
