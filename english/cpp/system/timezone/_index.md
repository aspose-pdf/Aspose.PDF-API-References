---
title: System::TimeZone class
linktitle: TimeZone
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZone class. Represents a time zone. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 6200
url: /cpp/system/timezone/
---
## TimeZone class


Represents a time zone. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TimeZone : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [get_CurrentTimeZone](./get_currenttimezone/)() | Returns a new instance of [TimeZone](./) class that represents the current time zone. |
| virtual [get_DaylightName](./get_daylightname/)() const | Returns a name for the daylight saving time of the time zone represented by the current object. |
| virtual [get_StandardName](./get_standardname/)() const | Returns a name for the standard time of the time zone represented by the current object. |
| virtual [GetDaylightChanges](./getdaylightchanges/)(int32_t) | Returns the daylight saving time period for a particular year. |
| virtual [GetUtcOffset](./getutcoffset/)(DateTime) | Returns the UTC offset for the specified local time. |
| virtual [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) | Determines if the date and time value represented by the specified [DateTime](../datetime/) object falls in the range of daylight saving time for the time zone represented by the current [TimeZone](./) object. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
