---
title: System::DateTimeOffset class
linktitle: DateTimeOffset
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTimeOffset class. Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1700
url: /cpp/system/datetimeoffset/
---
## DateTimeOffset class


Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeOffset
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Adds a specified time interval to the [DateTimeOffset](./) object. |
| [AddDays](./adddays/)(double) const | Adds a specified number of days to the [DateTimeOffset](./) object. |
| [AddHours](./addhours/)(double) const | Adds a specified number of hours to the [DateTimeOffset](./) object. |
| [AddMilliseconds](./addmilliseconds/)(double) const | Adds a specified number of milliseconds to the [DateTimeOffset](./) object. |
| [AddMinutes](./addminutes/)(double) const | Adds a specified number of minutes to the [DateTimeOffset](./) object. |
| [AddMonths](./addmonths/)(int) const | Adds a specified number of months to the [DateTimeOffset](./) object. |
| [AddSeconds](./addseconds/)(double) const | Adds a specified number of seconds to the [DateTimeOffset](./) object. |
| [AddTicks](./addticks/)(int64_t) const | Adds a specified number of ticks to the [DateTimeOffset](./) object. |
| [AddYears](./addyears/)(int) const | Adds a specified number of years to the [DateTimeOffset](./) object. |
| static [Compare](./compare/)(const DateTimeOffset\&, const DateTimeOffset\&) | Compares two [DateTimeOffset](./) objects. |
| [CompareTo](./compareto/)(const DateTimeOffset\&) const | Compares two [DateTimeOffset](./) objects. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Compares two [DateTimeOffset](./) objects. |
| [DateTimeOffset](./datetimeoffset/)() | Default constructor. |
| [DateTimeOffset](./datetimeoffset/)(DateTime) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int64_t, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(DateTime, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, TimeSpan) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) | Constructor. |
| static [Equals](./equals/)(const DateTimeOffset\&, const DateTimeOffset\&) | Checks if two [DateTimeOffset](./) objects represent the same time point. |
| [Equals](./equals/)(const DateTimeOffset\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point. |
| [EqualsExact](./equalsexact/)(const DateTimeOffset\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point and has the same offset. |
| [EqualsExact](./equalsexact/)(const SharedPtr\<Object\>\&) const | Checks if two [DateTimeOffset](./) objects represents the same time point and has the same offset. |
| static [FromFileTime](./fromfiletime/)(int64_t) | [Convert](../convert/)[Windows](../../system.windows/) file time to date and time with local time offset. |
| static [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(int64_t) | [Convert](../convert/) Unix-time to [DateTimeOffset](./) object. |
| static [FromUnixTimeSeconds](./fromunixtimeseconds/)(int64_t) | [Convert](../convert/) Unix-time to [DateTimeOffset](./) object. |
| [get_Date](./get_date/)() const | Gets date component of the current object. |
| [get_DateTime](./get_datetime/)() const | Gets [DateTime](../datetime/) value. |
| [get_Day](./get_day/)() const | Gets day of the month of the current object. |
| [get_DayOfWeek](./get_dayofweek/)() const | Gets day of the week of the current object. |
| [get_DayOfYear](./get_dayofyear/)() const | Gets day of year of the current object. |
| [get_Hour](./get_hour/)() const | Gets hour component of the current object. |
| [get_LocalDateTime](./get_localdatetime/)() const | Gets [DateTime](../datetime/) value that represents the local date and time. |
| [get_Millisecond](./get_millisecond/)() const | Gets millisecond component of the current object. |
| [get_Minute](./get_minute/)() const | Gets minute component of the current object. |
| [get_Month](./get_month/)() const | Gets month component of the current object. |
| static [get_Now](./get_now/)() | Gets [DateTimeOffset](./) whose date and time are set to the current local-time and whose offset is set to local time's offset. |
| [get_Offset](./get_offset/)() const | Gets offset from UTC. |
| [get_Second](./get_second/)() const | Gets second component of the current object. |
| [get_Ticks](./get_ticks/)() const | Gets number of ticks of the current object. |
| [get_TimeOfDay](./get_timeofday/)() const | Gets time of day of the current object. |
| [get_UtcDateTime](./get_utcdatetime/)() const | Gets [DateTime](../datetime/) value that represents the UTC date and time. |
| static [get_UtcNow](./get_utcnow/)() | Gets [DateTimeOffset](./) whose date and time are set to the current UTC-time and whose offset is [TimeSpan::Zero](../timespan/zero/). |
| [get_UtcTicks](./get_utcticks/)() const | Gets number of ticks of the current object in UTC time. |
| [get_Year](./get_year/)() const | Gets year component of the current object. |
| [GetHashCode](./gethashcode/)() const | Gets hash code for the current [DateTimeOffset](./) object. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(const DateTimeOffset\&) const | Determines if the current object and the specified [DateTimeOffset](./) object represent distinct date and time values. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Returns a new instance of [DateTimeOffset](./) class that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [operator-](./operator-/)(TimeSpan) const | Returns a new instance of the [DateTimeOffset](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| [operator-](./operator-/)(const DateTimeOffset\&) const | Returns an instance of [TimeSpan](../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects. |
| [operator<](./operator_/)(const DateTimeOffset\&) const | Determines if the current object represents the date and time value that is earlier than the value represented by the specified [DateTimeOffset](./) object. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(const DateTimeOffset\&) const | Determines if the current object represents the date and time value that is earlier than or the same as the value represented by the specified [DateTimeOffset](./) object. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator==](./operator==/)(const DateTimeOffset\&) const | Determines if the current object and the specified [DateTimeOffset](./) object represent the same date and time value. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(const DateTimeOffset\&) const | Determines if the current object represents the date and time value that is later than the value represented by the specified [DateTimeOffset](./) object. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(const DateTimeOffset\&) const | Determines if the current object represents the date and time value that is later than or the same as the value represented by the specified [DateTimeOffset](./) object. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Converts the specified string to [DateTimeOffset](./) equivalent. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string to [DateTimeOffset](./) object using the specified format provider and formatting style. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string to [DateTimeOffset](./) object using the specified format, format provider and formatting style. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string to [DateTimeOffset](./) object using the specified formats, format provider and formatting style. |
| [Subtract](./subtract/)(TimeSpan) const | Subtracts a specified time interval from the current object. |
| [Subtract](./subtract/)(const DateTimeOffset\&) const | Subtracts a specified [DateTimeOffset](./) value from the current object. |
| [ToFileTime](./tofiletime/)() const | Converts current object to the [Windows](../../system.windows/) file time. |
| [ToLocalTime](./tolocaltime/)() const | Converts current object to a object that represents the local time,. |
| [ToOffset](./tooffset/)(TimeSpan) const | Replace current object offset by the specified offset. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Converts current object to string using the specified format and format provider. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Converts current object to string using the specified format provider. |
| [ToString](./tostring/)(const String\&) const | Converts current object to string using the specified format. |
| [ToString](./tostring/)() const | Converts current object to string. |
| [ToUniversalTime](./touniversaltime/)() const | Converts current object to a object that represents the UTC time,. |
| [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Gets milliseconds elapsed from Unix epoch start. |
| [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Gets seconds elapsed from Unix epoch start. |
| static [TryParse](./tryparse/)(const String\&, DateTimeOffset\&) | Tries to converts the specified string to [DateTimeOffset](./) object. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified format provider and formatting style. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified formats, format provider and formatting style. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Tries to converts the specified string to [DateTimeOffset](./) object using the specified format, format provider and formatting style. |
| static [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that represent [TimeSpan](../timespan/) structure. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Gets maximum offset in ticks. |
| static [MaxValue](./maxvalue/) | Gets greatest [DateTimeOffset](./) value. |
| static constexpr [MinOffset](./minoffset/) | Gets minimum offset in ticks. |
| static [MinValue](./minvalue/) | Gets earliest [DateTimeOffset](./) value. |
| static [UnixEpoch](./unixepoch/) | Gets Unix epoch start. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
