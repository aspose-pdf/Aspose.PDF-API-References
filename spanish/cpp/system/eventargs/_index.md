---
title: "Clase System::EventArgs"
linktitle: "EventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::EventArgs class. La clase base para clases que representan un contexto que se pasa a los suscriptores del evento cuando se dispara un evento. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system/eventargs/
---
## EventArgs class


La clase base para clases que representan un contexto que se pasa a los suscriptores del evento cuando se dispara un evento. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EventArgs : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EventArgs](./eventargs/)() | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](./) (puntero nulo). |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
