---
title: System::ComponentModel::AsyncCompletedEventArgs class
linktitle: AsyncCompletedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::AsyncCompletedEventArgs class. An instance of this class is passed as the argument on to the AsyncCompletedEventHandler delegate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.componentmodel/asynccompletedeventargs/
---
## AsyncCompletedEventArgs class


An instance of this class is passed as the argument on to the AsyncCompletedEventHandler delegate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AsyncCompletedEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)() | Constructor. |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) | Initializes a new instance of the [System.ComponentModel.AsyncCompletedEventArgs](./) class. |
| [get_Cancelled](./get_cancelled/)() const | Gets a value indicating whether an asynchronous operation has been canceled. true if the background operation has been canceled; otherwise false. The default is false. |
| [get_Error](./get_error/)() const | Gets a value indicating which error occurred during an asynchronous operation. |
| [get_UserState](./get_userstate/)() const | Gets the unique identifier for the asynchronous task. An object reference that uniquely identifies the asynchronous task; otherwise, null if no value has been set. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
