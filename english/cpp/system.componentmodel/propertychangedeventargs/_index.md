---
title: System::ComponentModel::PropertyChangedEventArgs class
linktitle: PropertyChangedEventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::PropertyChangedEventArgs class. Arguments of PropertyChanged event. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.componentmodel/propertychangedeventargs/
---
## PropertyChangedEventArgs class


Arguments of PropertyChanged event. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PropertyChangedEventArgs : public System::EventArgs
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_PropertyName](./get_propertyname/)() | RTTI information. |
| [PropertyChangedEventArgs](./propertychangedeventargs/)(const String\&) | Initializes PropertyChanged event arguments. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | A static member that represents an "empty" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## See Also

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
