---
title: System::Diagnostics::StackTrace class
linktitle: StackTrace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::StackTrace class. Collection of stack frames. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.diagnostics/stacktrace/
---
## StackTrace class


Collection of stack frames. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StackTrace : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_FrameCount](./get_framecount/)() const | Gets count of frames in stack trace. |
| virtual [GetFrame](./getframe/)(uint32_t) | Gets stack frame. |
| [operator=](./operator=/)(const StackTrace\&) const | No assignment. |
| [StackTrace](./stacktrace/)() | Creates stack trace describing current stack state. |
| [StackTrace](./stacktrace/)(bool) | Creates stack trace describing current stack state. |
| [StackTrace](./stacktrace/)(const StackTrace\&) | No copying. |
| virtual [~StackTrace](./~stacktrace/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
