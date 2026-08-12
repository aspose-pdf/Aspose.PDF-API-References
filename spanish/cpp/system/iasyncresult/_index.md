---
title: "System::IAsyncResult clase"
linktitle: "IAsyncResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IAsyncResult clase. Representa el estado de una operación asíncrona. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3200
url: /es/cpp/system/iasyncresult/
---
## IAsyncResult class


Representa el estado de una operación asíncrona. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class IAsyncResult : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_AsyncState](./get_asyncstate/)() | Devuelve un objeto que contiene la información sobre la operación asíncrona. |
| virtual [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Devuelve una instancia de WaitHandle que puede usarse para esperar la finalización de la operación asíncrona. |
| virtual [get_CompletedSynchronously](./get_completedsynchronously/)() | Devuelve un valor que indica si la operación asíncrona se completó de forma síncrona. |
| virtual [get_IsCompleted](./get_iscompleted/)() | Devuelve un valor que indica si la operación asíncrona ha finalizado. |
| virtual [~IAsyncResult](./~iasyncresult/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Puntero compartido a [IAsyncResult](./). |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
