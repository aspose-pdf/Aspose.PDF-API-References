---
title: "Clase System::ComponentModel::DoWorkEventArgs"
linktitle: "DoWorkEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::DoWorkEventArgs. Argumentos del evento DoWork. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.componentmodel/doworkeventargs/
---
## DoWorkEventArgs class


Argumentos del evento DoWork. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class DoWorkEventArgs : public System::ComponentModel::CancelEventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DoWorkEventArgs](./doworkeventargs/)(const SharedPtr\<System::Object\>\&) | Información RTTI. |
| [get_Argument](./get_argument/)() | Obtiene la propiedad Argument; no implementado. |
| [get_Result](./get_result/)() | Obtiene la propiedad Result; no implementado. |
| [set_Result](./set_result/)(const SharedPtr\<System::Object\>\&) | Establece la propiedad Result; no implementado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [CancelEventArgs](../canceleventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
