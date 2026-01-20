---
title: System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs constructor
linktitle: AsyncCompletedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs constructor. Constructor in C++.'
type: docs
weight: 100
url: /cpp/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## See Also

* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Initializes a new instance of the [System.ComponentModel.AsyncCompletedEventArgs](../) class.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| error | const System::Exception\& | Any error that occurred during the asynchronous operation. |
| canceled | bool | A value indicating whether the asynchronous operation was canceled. |
| userState | const System::SharedPtr\<System::Object\>\& | The optional user-supplied state object passed to the [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) method. |

## See Also

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [AsyncCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
