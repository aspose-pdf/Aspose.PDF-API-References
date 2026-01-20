---
title: System::Globalization::DaylightTime class
linktitle: DaylightTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::DaylightTime class. Period of daylight saving time. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.globalization/daylighttime/
---
## DaylightTime class


Period of daylight saving time. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DaylightTime : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [DaylightTime](./daylighttime/)(DateTime, DateTime, TimeSpan) | RTTI information. |
| [get_Delta](./get_delta/)() const | Gets difference between standard time and daylight saving time. |
| [get_End](./get_end/)() const | Gets date and time when daylight saving time ends. |
| [get_Start](./get_start/)() const | Gets date and time when daylight saving time begins. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
