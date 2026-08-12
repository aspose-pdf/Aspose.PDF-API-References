---
title: "Clase System::Diagnostics::TraceListener"
linktitle: "TraceListener"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Diagnostics::TraceListener. Interfaz para reaccionar a la información de depuración y rastreo. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.diagnostics/tracelistener/
---
## TraceListener class


Interfaz para reaccionar a la información de depuración y rastreo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class TraceListener : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Fail](./fail/)(System::String) | Escribe un mensaje de error en el depurador. |
| virtual [Fail](./fail/)(System::String, System::String) | Escribe un mensaje de error en el depurador. |
| virtual [Write](./write/)(System::String) | Información RTTI. |
| virtual [WriteLine](./writeline/)(System::String) | Escribe una línea en el depurador. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
