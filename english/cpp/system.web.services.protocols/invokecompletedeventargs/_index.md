---
title: System::Web::Services::Protocols::InvokeCompletedEventArgs class
linktitle: InvokeCompletedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::Protocols::InvokeCompletedEventArgs class. An instance of this class is passed as the argument on to the InvokeCompletedEventHandler delegate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.web.services.protocols/invokecompletedeventargs/
---
## InvokeCompletedEventArgs class


An instance of this class is passed as the argument on to the InvokeCompletedEventHandler delegate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class InvokeCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_Results](./get_results/)() | Returns a collection of asynchronous operation results. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/)(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Constructs a new instance. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
