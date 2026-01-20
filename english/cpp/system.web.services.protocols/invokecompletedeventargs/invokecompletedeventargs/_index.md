---
title: System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor
linktitle: InvokeCompletedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor. Constructs a new instance in C++.'
type: docs
weight: 100
url: /cpp/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs constructor


Constructs a new instance.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


| Parameter | Type | Description |
| --- | --- | --- |
| error | Exception | Any error that occurred during an asynchronous operation. |
| cancelled | bool | A value that indicates if an asynchronous operation is canceled. |
| userState | System::SharedPtr\<Object\> | The optional user-supplied state object passed to the [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) method. |
| results | System::ArrayPtr\<System::SharedPtr\<Object\>\> | A collection of asynchronous operation results. |

## See Also

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [InvokeCompletedEventArgs](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.PDF for C++](../../../)
