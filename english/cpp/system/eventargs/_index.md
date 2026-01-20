---
title: System::EventArgs class
linktitle: EventArgs
second_title: Aspose.PDF for C++ API Reference
description: 'System::EventArgs class. The base class for classes that represent a context that is passed to the event subscribers when an event is triggered. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system/eventargs/
---
## EventArgs class


The base class for classes that represent a context that is passed to the event subscribers when an event is triggered. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EventArgs : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [EventArgs](./eventargs/)() | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | A static member that represents an "empty" [EventArgs](./) shared pointer (null-pointer). |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
