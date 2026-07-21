---
title: "System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor"
linktitle: "InvokeCompletedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor. Construye una nueva instancia en C++."
type: docs
weight: 100
url: /es/cpp/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor


Construye una nueva instancia.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| error | Exception | Cualquier error que ocurrió durante una operación asíncrona. |
| cancelado | bool | Un valor que indica si una operación asíncrona está cancelada. |
| userState | System::SharedPtr\<Object\> | El objeto de estado opcional suministrado por el usuario que se pasa al método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| resultados | System::ArrayPtr\<System::SharedPtr\<Object\>\> | Una colección de resultados de operaciones asíncronas. |

## Ver también

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [InvokeCompletedEventArgs](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.PDF for C++](../../../)
