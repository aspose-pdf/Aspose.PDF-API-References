---
title: "Clase System::ComponentModel::AsyncCompletedEventArgs"
linktitle: "AsyncCompletedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::AsyncCompletedEventArgs. Una instancia de esta clase se pasa como argumento al delegado AsyncCompletedEventHandler. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.componentmodel/asynccompletedeventargs/
---
## AsyncCompletedEventArgs class


Una instancia de esta clase se pasa como argumento al delegado AsyncCompletedEventHandler. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class AsyncCompletedEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)() | Constructor. |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) | Inicializa una nueva instancia de la clase [System.ComponentModel.AsyncCompletedEventArgs](./). |
| [get_Cancelled](./get_cancelled/)() const | Obtiene un valor que indica si una operación asíncrona ha sido cancelada. true si la operación en segundo plano ha sido cancelada; de lo contrario, false. El valor predeterminado es false. |
| [get_Error](./get_error/)() const | Obtiene un valor que indica qué error ocurrió durante una operación asíncrona. |
| [get_UserState](./get_userstate/)() const | Obtiene el identificador único para la tarea asíncrona. Una referencia a un objeto que identifica de forma única la tarea asíncrona; de lo contrario, null si no se ha establecido ningún valor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
