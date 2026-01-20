---
title: System::Text::RegularExpressions::Capture class
linktitle: Capture
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Capture class. Result of single subexpression matching. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.text.regularexpressions/capture/
---
## Capture class


Result of single subexpression matching. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Capture : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Capture](./capture/)(const UStringPtr\&, int, int) | Constructor. |
| [get_Index](./get_index/)() const | Gets index of captured substring. |
| [get_Length](./get_length/)() const | Gets length of captured substring. |
| [get_Value](./get_value/)() const | Gets captured substring. |
| [ToString](./tostring/)() const override | Gets captured substring. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
