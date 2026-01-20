---
title: System::Diagnostics::TraceListener class
linktitle: TraceListener
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::TraceListener class. Interface to react to debug and trace infofmation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.diagnostics/tracelistener/
---
## TraceListener class


Interface to react to debug and trace infofmation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TraceListener : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Fail](./fail/)(System::String) | Writes failure message to debugger. |
| virtual [Fail](./fail/)(System::String, System::String) | Writes failure message to debugger. |
| virtual [Write](./write/)(System::String) | RTTI information. |
| virtual [WriteLine](./writeline/)(System::String) | Writes line to debugger. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
