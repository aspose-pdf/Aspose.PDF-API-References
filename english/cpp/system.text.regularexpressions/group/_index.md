---
title: System::Text::RegularExpressions::Group class
linktitle: Group
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Group class. Result of matching done by single capturing group. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.text.regularexpressions/group/
---
## Group class


Result of matching done by single capturing group. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Methods

| Method | Description |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Adds capture into group. |
| [get_Captures](./get_captures/)() | Gets available captures. |
| [get_Success](./get_success/)() | Checks if capturing was successful for this group. |
| [Group](./group/)(const UStringPtr\&, int, int) | Constructor. |
| [Group](./group/)() | Constructor of empty group. |
## See Also

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
