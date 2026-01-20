---
title: System::ComponentModel::ProgressChangedEventArgs class
linktitle: ProgressChangedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::ProgressChangedEventArgs class. An instance of this class is passed as the argument on to the ProgressChangedEventHandler delegate. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.componentmodel/progresschangedeventargs/
---
## ProgressChangedEventArgs class


An instance of this class is passed as the argument on to the ProgressChangedEventHandler delegate. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ProgressChangedEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| [get_ProgressPercentage](./get_progresspercentage/)() const | Gets the asynchronous task progress percentage. |
| [get_UserState](./get_userstate/)() const | Gets a unique user state. |
| [ProgressChangedEventArgs](./progresschangedeventargs/)(int, System::SharedPtr\<System::Object\>) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
