---
title: System::TimeZoneInfo::AdjustmentRule class
linktitle: AdjustmentRule
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo::AdjustmentRule class. Provides information about a time zone adjustment. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3300
url: /cpp/system/timezoneinfo/adjustmentrule/
---
## AdjustmentRule class


Provides information about a time zone adjustment. Objects of this class should only be allocated using [System::MakeObject()](../../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AdjustmentRule : public System::IEquatable<AdjustmentRulePtr>
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) | Constructs an instance of [AdjustmentRule](./) class that represents a time adjustment rule described with the specified parameters. |
| static [CreateAdjustmentRule](./createadjustmentrule/)(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) | Constructs an instance of [AdjustmentRule](./) class that represents a time adjustment rule described with the specified parameters. |
| [Equals](./equals/)(AdjustmentRulePtr) override |  |
| [get_BaseUtcOffsetDelta](./get_baseutcoffsetdelta/)() const | Returns a delta from the default UTC offset. |
| [get_DateEnd](./get_dateend/)() const | Returns a [DateTime](../../datetime/) object that represents the date and time when the adjustment rule stops being effective. |
| [get_DateStart](./get_datestart/)() const | Returns a [DateTime](../../datetime/) object that represents the date and time when the adjustment rule comes into effect. |
| [get_DaylightDelta](./get_daylightdelta/)() const | Returns in [TimeSpan](../../timespan/) object that represents the amount of time required to form the daylight saving time of the time zone. |
| [get_DaylightTransitionEnd](./get_daylighttransitionend/)() const | Returns the information about transition from standard time to daylight saving time. |
| [get_DaylightTransitionStart](./get_daylighttransitionstart/)() const | Returns the information about transition from daylight saving time to standard time. |
| [get_HasDaylightSaving](./get_hasdaylightsaving/)() const | FOR INTERNAL USE. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../object/gethashcode/) method. Enables hashing of custom objects. |
## See Also

* Class [IEquatable](../../iequatable/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
