---
title: System::Diagnostics::StackFrame class
linktitle: StackFrame
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::StackFrame class. Gets information on single stack frame. MSVS only. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.diagnostics/stackframe/
---
## StackFrame class


Gets information on single stack frame. MSVS only. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StackFrame : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetFileColumnNumber](./getfilecolumnnumber/)() | Gets the colnum number. |
| virtual [GetFileLineNumber](./getfilelinenumber/)() | Gets the line number. |
| virtual [GetFileName](./getfilename/)() | Gets the file name. |
| [GetMethod](./getmethod/)() | Gets method information. |
| [operator=](./operator=/)(const StackFrame\&) const | No changing. |
| [StackFrame](./stackframe/)(int) | Creates stack frame on current stack offset. |
| [StackFrame](./stackframe/)(const StackFrame\&) | No copying. |
| virtual [~StackFrame](./~stackframe/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
