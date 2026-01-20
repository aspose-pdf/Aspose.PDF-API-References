---
title: System::ComponentModel::DoWorkEventArgs class
linktitle: DoWorkEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::DoWorkEventArgs class. DoWork event arguments. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.componentmodel/doworkeventargs/
---
## DoWorkEventArgs class


DoWork event arguments. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DoWorkEventArgs : public System::ComponentModel::CancelEventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [DoWorkEventArgs](./doworkeventargs/)(const SharedPtr\<System::Object\>\&) | RTTI information. |
| [get_Argument](./get_argument/)() | Gets Argument property; not implemented. |
| [get_Result](./get_result/)() | Gets Result property; not implemented. |
| [set_Result](./set_result/)(const SharedPtr\<System::Object\>\&) | Sets Result property; not implemented. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [CancelEventArgs](../canceleventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
