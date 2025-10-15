---
title: System::Threading::WaitHandle class
linktitle: WaitHandle
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::WaitHandle class. Waiting primitive base class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1700
url: /cpp/system.threading/waithandle/
---
## WaitHandle class


Waiting primitive base class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WaitHandle : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | Releases any resource associated with handle. |
| [get_Handle](./get_handle/)() | Gets handle. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | RTTI information. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Waits for all handles to fire. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Waits for all handles to fire. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Waits for any of the handles to fire. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Waits for any of the handles to fire. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Waits for any of the handles to fire. |
| virtual [WaitOne](./waitone/)() | Waits for the handle to fire for unlimited period. |
| virtual [WaitOne](./waitone/)(int) | Waits for the handle to fire. |
| virtual [WaitOne](./waitone/)(TimeSpan) | Waits for the handle to fire. |
| virtual [WaitOne](./waitone/)(int, bool) | Waits for the handle to fire. |
| virtual [~WaitHandle](./~waithandle/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Special value to be returned by the function otherwise returning index of signalled object in array, if timeout exceeds and nothing signals. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
