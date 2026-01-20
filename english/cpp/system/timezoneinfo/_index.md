---
title: System::TimeZoneInfo class
linktitle: TimeZoneInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeZoneInfo class. Represents an information destribing a particular time zone. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 6300
url: /cpp/system/timezoneinfo/
---
## TimeZoneInfo class


Represents an information destribing a particular time zone. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Nested classes

* Class [AdjustmentRule](./adjustmentrule/)
* Class [TransitionTime](./transitiontime/)
## Methods

| Method | Description |
| --- | --- |
| static [ClearCachedData](./clearcacheddata/)() | Clear cached time zone data. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) time from one time zone to another. |
| static [ConvertTime](./converttime/)(const DateTimeOffset\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) time to the time in a specified time zone. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&) | [Convert](../convert/) time to the time in a specified time zone. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&) | [Convert](../convert/) time to the time in a specified time zone. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const DateTimeOffset\&, const String\&) | [Convert](../convert/) time to the time in a specified time zone. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&, const String\&) | [Convert](../convert/) time to the time in a specified time zone. |
| static [ConvertTimeFromUtc](./converttimefromutc/)(DateTime, const TimeZoneInfoPtr\&) | Converts UTC-time to the time in a specified time zone. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime, const TimeZoneInfoPtr\&) | Converts time to UTC-time. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime) | Converts time to UTC-time. |
| static [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)(DateTime) | Converts time to UTC-time. FOR INTERNAL USE. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) | Creates a custom time zone. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) | Creates a custom time zone. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&) | Creates a custom time zone. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(TimeZoneInfoPtr) override | Determines if the the current and specified objects are equal. |
| static [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const String\&) | Gets time zone with specified identifier. |
| [get_BaseUtcOffset](./get_baseutcoffset/)() const | Returns an instance of [TimeSpan](../timespan/) that represents a time interval between the current time zone's standard time and UTC time. |
| [get_DaylightName](./get_daylightname/)() const | Gets name for the current time zone's daylight saving time. |
| [get_DisplayName](./get_displayname/)() const | Gets name for the current time zone. |
| [get_Id](./get_id/)() const | Returns the identifier of the time zone represented by the current object. |
| static [get_Local](./get_local/)() | Returns an instance of [TimeZoneInfo](./) that represents a local time zone. |
| [get_StandardName](./get_standardname/)() const | Gets name for the current time zone's standart time. |
| [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Gets flag indicating if time zone has daylight saving time rules. |
| static [get_Utc](./get_utc/)() | Returns an instance of [TimeZoneInfo](./) that represents a UTC time zone. |
| [GetAdjustmentRules](./getadjustmentrules/)() const | Returns an array consisting of [AdjustmentRule](./adjustmentrule/) objects that represent adjustment rules that apply to the current [TimeZoneInfo](./) object. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(DateTime) const | Gets UTC dates and times that a specified date and time can be mapped to. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const DateTimeOffset\&) const | Gets UTC dates and times that a specified date and time can be mapped to. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetSystemTimeZones](./getsystemtimezones/)() | Gets sorted collection of all time zones available on the local system. |
| [GetUtcOffset](./getutcoffset/)(DateTime) const | Calculates difference between time in this time zone and UTC time zone for a specified date and time. |
| [GetUtcOffset](./getutcoffset/)(const DateTimeOffset\&) const | Calculates difference between time in this time zone and UTC time zone for a specified date and time. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&) | Internal helper function that returns the UTC offset for a UTC-datetime in a specified time zone. FOR INTERNAL USE. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&, bool\&, bool\&) | Internal helper function that returns the UTC offset for a UTC-datetime in a specified time zone. FOR INTERNAL USE. |
| [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)(DateTime) const | Calculates difference between time in this time zone and UTC time zone for a specified date and time. FOR INTERNAL USE. |
| [HasSameRules](./hassamerules/)(const TimeZoneInfoPtr\&) const | Checks if current and another time zones have the same adjustment rules. |
| [IsAmbiguousTime](./isambiguoustime/)(DateTime) const | Checks if specified date and time is ambiguous and can be mapped to many UTC times. |
| [IsAmbiguousTime](./isambiguoustime/)(const DateTimeOffset\&) const | Checks if specified date and time is ambiguous and can be mapped to many UTC times. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) const | Checks if specified date and time falls in range of daylight saving time. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(const DateTimeOffset\&) const | Checks if specified date and time falls in range of daylight saving time. |
| [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)(DateTime) const | Checks if specified date and time falls in range of daylight saving time. |
| [IsInvalidTime](./isinvalidtime/)(DateTime) const | Checks if specified date and time is invalid. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../object/tostring/) method. Enables converting custom objects to string. |
| static [TransitionTimeToDateTime](./transitiontimetodatetime/)(int32_t, const TransitionTime\&) | Helper function that converts a year and [TransitionTime](./transitiontime/) into a [DateTime](../datetime/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | An alias for a shared pointer to an instance of [AdjustmentRule](./adjustmentrule/) class. |
## See Also

* Class [IEquatable](../iequatable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
