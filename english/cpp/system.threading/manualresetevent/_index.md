---
title: System::Threading::ManualResetEvent class
linktitle: ManualResetEvent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::ManualResetEvent class. Event to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


[Event](../../system/event/) to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Methods

| Method | Description |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | RTTI information. |
## Fields

| Field | Description |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Special value to be returned by the function otherwise returning index of signalled object in array, if timeout exceeds and nothing signals. |
## See Also

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
