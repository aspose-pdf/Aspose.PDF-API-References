---
title: "System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs-konstruktor"
linktitle: "InvokeCompletedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs konstruktor. Skapar en ny instans i C++."
type: docs
weight: 100
url: /sv/cpp/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor


Skapar en ny instans.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fel | Exception | Alla fel som inträffade under en asynkron operation. |
| avbruten | bool | Ett värde som indikerar om en asynkron operation har avbrutits. |
| userState | System::SharedPtr\<Object\> | Det valfria användarlevererade tillståndsobjektet som skickas till metoden [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| resultat | System::ArrayPtr\<System::SharedPtr\<Object\>\> | En samling av resultat från asynkrona operationer. |

## Se även

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [InvokeCompletedEventArgs](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.PDF for C++](../../../)
