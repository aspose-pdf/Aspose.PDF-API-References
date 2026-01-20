---
title: System::ComponentModel::CancelEventArgs class
linktitle: CancelEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::CancelEventArgs class. Arguments of cancellable event. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.componentmodel/canceleventargs/
---
## CancelEventArgs class


Arguments of cancellable event. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CancelEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [CancelEventArgs](./canceleventargs/)(bool) | RTTI information. |
| [CancelEventArgs](./canceleventargs/)() | Constructor; sets Cancel property to false. |
| [get_Cancel](./get_cancel/)() | Gets value indicating whether the event should be cancelled. |
| [set_Cancel](./set_cancel/)(bool) | Sets value indicating whether the event should be cancelled. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
