---
title: System::Threading::EventWaitHandle class
linktitle: EventWaitHandle
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::EventWaitHandle class. Event that can be sent to waiting thread. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


[Event](../../system/event/) that can be sent to waiting thread. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Methods

| Method | Description |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | RTTI information. |
| virtual [Reset](./reset/)() | Sets event to non-signalling state. |
| virtual [Set](./set/)() | Sets event to signalling state. |
| [~EventWaitHandle](./~eventwaithandle/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Special value to be returned by the function otherwise returning index of signalled object in array, if timeout exceeds and nothing signals. |
## See Also

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
