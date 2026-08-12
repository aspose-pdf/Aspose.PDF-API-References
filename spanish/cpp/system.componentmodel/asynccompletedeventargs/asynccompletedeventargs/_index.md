---
title: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs constructor"
linktitle: "AsyncCompletedEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs constructor. Constructor en C++."
type: docs
weight: 100
url: /es/cpp/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## Ver también

* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Inicializa una nueva instancia de la clase [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| error | const System::Exception\& | Cualquier error que ocurra durante la operación asíncrona. |
| cancelado | bool | Un valor que indica si la operación asíncrona fue cancelada. |
| userState | const System::SharedPtr\<System::Object\>\& | El objeto de estado opcional suministrado por el usuario que se pasa al método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Ver también

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
