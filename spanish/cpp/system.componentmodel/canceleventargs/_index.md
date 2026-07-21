---
title: "Clase System::ComponentModel::CancelEventArgs"
linktitle: "CancelEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::CancelEventArgs. Argumentos de un evento cancelable. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.componentmodel/canceleventargs/
---
## CancelEventArgs class


Argumentos de un evento cancelable. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class CancelEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CancelEventArgs](./canceleventargs/)(bool) | Información RTTI. |
| [CancelEventArgs](./canceleventargs/)() | Constructor; establece la propiedad Cancel en false. |
| [get_Cancel](./get_cancel/)() | Obtiene el valor que indica si el evento debe cancelarse. |
| [set_Cancel](./set_cancel/)(bool) | Establece el valor que indica si el evento debe cancelarse. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
