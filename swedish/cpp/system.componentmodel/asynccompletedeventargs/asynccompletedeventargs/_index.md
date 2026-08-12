---
title: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs-konstruktör"
linktitle: "AsyncCompletedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs-konstruktör. Konstruktor i C++."
type: docs
weight: 100
url: /sv/cpp/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## Se även

* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Initierar en ny instans av klassen [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fel | const System::Exception\& | Alla fel som inträffade under den asynkrona operationen. |
| avbruten | bool | Ett värde som indikerar om den asynkrona operationen avbröts. |
| userState | const System::SharedPtr\<System::Object\>\& | Det valfria användarlevererade tillståndsobjektet som skickas till metoden [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Se även

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
