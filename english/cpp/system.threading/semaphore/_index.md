---
title: System::Threading::Semaphore class
linktitle: Semaphore
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Semaphore class. Semaphore implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.threading/semaphore/
---
## Semaphore class


[Semaphore](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Methods

| Method | Description |
| --- | --- |
| [Release](./release/)() | Releases lock on semaphore. |
| [Release](./release/)(int) | Releases multiple locks on semaphore. |
| virtual [Reset](./reset/)() | Sets semaphore to non-signalled state. Not supported. |
| [Semaphore](./semaphore/)(int, int) | RTTI information. |
| [Semaphore](./semaphore/)(int, int, const String\&) | Creates named semaphore. |
| [Semaphore](./semaphore/)(int, int, const String\&, bool\&) | Creates named semaphore. |
| virtual [Set](./set/)() | Sets semaphore to signalled state. Not supported. |
| [WaitOne](./waitone/)() override | Locks semaphore. Performs unlimited waiting if neccessary. |
| [WaitOne](./waitone/)(int) override | Locks semaphore. Performs waiting if neccessary. |
## Fields

| Field | Description |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Special value to be returned by the function otherwise returning index of signalled object in array, if timeout exceeds and nothing signals. |
## See Also

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
