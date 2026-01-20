---
title: System::ComponentModel::RunWorkerCompletedEventArgs class
linktitle: RunWorkerCompletedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::RunWorkerCompletedEventArgs class. An instance of this class is passed as the argument to the RunWorkerCompletedEventHandler delegate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.componentmodel/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs class


An instance of this class is passed as the argument to the RunWorkerCompletedEventHandler delegate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RunWorkerCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_Result](./get_result/)() const | Gets a value that represents the result of an asynchronous operation. |
| [RunWorkerCompletedEventArgs](./runworkercompletedeventargs/)(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) | RTTI information. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [AsyncCompletedEventArgs](../asynccompletedeventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
