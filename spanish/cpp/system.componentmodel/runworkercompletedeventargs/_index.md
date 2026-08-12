---
title: "Clase System::ComponentModel::RunWorkerCompletedEventArgs"
linktitle: "RunWorkerCompletedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::ComponentModel::RunWorkerCompletedEventArgs. Una instancia de esta clase se pasa como argumento al delegado RunWorkerCompletedEventHandler. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.componentmodel/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs class


Una instancia de esta clase se pasa como argumento al delegado RunWorkerCompletedEventHandler. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class RunWorkerCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Result](./get_result/)() const | Obtiene un valor que representa el resultado de una operación asíncrona. |
| [RunWorkerCompletedEventArgs](./runworkercompletedeventargs/)(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) | Información RTTI. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [AsyncCompletedEventArgs](../asynccompletedeventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
