---
title: "System::Diagnostics::StackTrace clase"
linktitle: "StackTrace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Diagnostics::StackTrace clase. Colección de marcos de pila. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.diagnostics/stacktrace/
---
## StackTrace class


Colección de marcos de pila. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class StackTrace : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FrameCount](./get_framecount/)() const | Obtiene el recuento de marcos en la traza de pila. |
| virtual [GetFrame](./getframe/)(uint32_t) | Obtiene el marco de pila. |
| [operator=](./operator=/)(const StackTrace\&) const | Sin asignación. |
| [StackTrace](./stacktrace/)() | Crea una traza de pila que describe el estado actual de la pila. |
| [StackTrace](./stacktrace/)(bool) | Crea una traza de pila que describe el estado actual de la pila. |
| [StackTrace](./stacktrace/)(const StackTrace\&) | Sin copia. |
| virtual [~StackTrace](./~stacktrace/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
