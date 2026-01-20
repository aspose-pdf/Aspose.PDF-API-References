---
title: System::DateTime class
linktitle: DateTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::DateTime class. Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1600
url: /cpp/system/datetime/
---
## DateTime class


Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class DateTime
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Returns a new instance of [DateTime](./) class that represents a date and time value that results from addition of the specified time span to the date and time value represented by the current object. |
| [AddDays](./adddays/)(double) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of days. |
| [AddHours](./addhours/)(double) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of hours. |
| [AddMilliseconds](./addmilliseconds/)(double) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of milliseconds. |
| [AddMinutes](./addminutes/)(double) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of minutes. |
| [AddMonths](./addmonths/)(int) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of months. |
| [AddSeconds](./addseconds/)(double) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of seconds. |
| [AddTicks](./addticks/)(int64_t) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the sum of the value represented by the current object and the specified number of 100-nanosecond intervals. |
| [AddYears](./addyears/)(int) const | Returns a new instance of the [DateTime](./) class representing the date and time value equal to that represented by the current object with the year component increased by the specified number. |
| static [Compare](./compare/)(DateTime, DateTime) | Compares two values represented by the specified instances of [DateTime](./) class and returns the value indicating values' relative positions on the time line. |
| [CompareTo](./compareto/)(DateTime) const | Compares two date and time values represented by the current object and the specified instance of [DateTime](./) class and returns the value indicating values' relative positions on the time line. |
| [DateTime](./datetime/)() | Constructs an instance that represents the smallest possible date and time value equal to MinValue. |
| [DateTime](./datetime/)(int, int, int) | Constructs an instance that represents a date and time value specified as a particular year, month and day. |
| [DateTime](./datetime/)(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Constructs an instance that represents a date and time value specified as a particular year, month and day in the specified calendar. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second. |
| [DateTime](./datetime/)(int, int, int, int, int, int, DateTimeKind) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second in the specified calendar. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, DateTimeKind) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) | Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond in the specified calendar. |
| [DateTime](./datetime/)(int64_t, DateTimeKind) | Construct an instance that represents a date and time value specified as a number of ticks. |
| [DateTime](./datetime/)(int64_t, DateTimeKind, bool) | Construct an instance that represents a date and time value specified as a number of ticks. FOR INTERNAL USE. |
| [DateTime](./datetime/)(const DateTime\&) | Copy-constructs an instance. |
| static [DaysInMonth](./daysinmonth/)(int, int) | Returns the number of days in the specified month of the specified year. |
| static [Equals](./equals/)(DateTime, DateTime) | Determines if the specified instances of [DateTime](./) class represent the same date and time value. |
| [Equals](./equals/)(DateTime) const | Determines if the specified instance of [DateTime](./) class represent the same date and time value as the current object. |
| static [FromBinary](./frombinary/)(int64_t) | Deserializes the date time value from the specified unsigned 64-bit integer and sets the new instance of [DateTime](./) class to that value. |
| static [FromFileTime](./fromfiletime/)(int64_t) | Converts the specified File time to an instance of [DateTime](./) class representing the same date and time value as local time. |
| static [FromFileTimeUtc](./fromfiletimeutc/)(int64_t) | Converts the specified File time to an instance of [DateTime](./) class representing the same date and time value as UTC time. |
| static [FromOADate](./fromoadate/)(double) | Returns an instance of [DateTime](./) class representing the date and time value equivalent to the specified OLE Automation Date. |
| static [FromUnixTime](./fromunixtime/)(time_t) | Converts the specified Unix time value to an instance of [DateTime](./) class. FOR INTERNAL USE. |
| [get_Date](./get_date/)() const | Returns a new instance of [DateTime](./) class that represents the date portion of the date and time represented by the current object with each component of the time portion set to 0. |
| [get_Day](./get_day/)() const | Returns the ordinal number of the day in the month represented by the current object. |
| [get_DayOfWeek](./get_dayofweek/)() const | Returns a value representing a day of week that is represented by the current object. |
| [get_DayOfYear](./get_dayofyear/)() const | Returns the ordinal number of the day in the year represented by the current object. |
| [get_Hour](./get_hour/)() const | Returns the hour component of the date and time value represented by the current object. |
| [get_Kind](./get_kind/)() const | Returns the value representing if the date and time represented by the current object is a local or UTC date and time or neither. |
| [get_Millisecond](./get_millisecond/)() const | Returns the millisecond component of the date and time value represented by the current object. |
| [get_Minute](./get_minute/)() const | Returns the minute component of the date and time value represented by the current object. |
| [get_Month](./get_month/)() const | Returns the ordinal number of the month in the year represented by the current object. |
| static [get_Now](./get_now/)() | Returns an instance of [DateTime](./) class that represents the current time as local time. |
| [get_Second](./get_second/)() const | Returns the second component of the date and time value represented by the current object. |
| [get_Ticks](./get_ticks/)() const | Returns a number of 100-nanosecond intervals passed since 0:00:00 UTC, January 1, 0001, in the Gregorian calendar until the date and time represented by the current object. |
| [get_TimeOfDay](./get_timeofday/)() const | Returns the value that represents the time interval from the beginning of the day represented by the current object till the date and time value represented by the current object. |
| static [get_Today](./get_today/)() | Returns an instance of [DateTime](./) class that represents the current date with each component of time portion of the value represented by the object set to 0. |
| static [get_UtcNow](./get_utcnow/)() | Returns an instance of [DateTime](./) class that represents the current time as UTC. |
| [get_Year](./get_year/)() const | Returns the year represented by the current object. |
| [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Gets date parts. FOR INTERNAL USE. |
| [GetDateTimeFormats](./getdatetimeformats/)() const | Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier. |
| [GetDateTimeFormats](./getdatetimeformats/)(const SharedPtr\<IFormatProvider\>\&) const | Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers and the specified format provider. |
| [GetDateTimeFormats](./getdatetimeformats/)(char_t, const SharedPtr\<IFormatProvider\>\&) const | Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier and format provider. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determines if the date and time value represented by the current object falls in the range of daylight saving time for the current time zone. |
| static [IsLeapYear](./isleapyear/)(int) | Determines of the specified year is a leap year. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(DateTime) const | Determines if the current object and the specified [DateTime](./) object represent distinct date and time values. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Returns a new instance of [DateTime](./) class that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [operator+=](./operator+=/)(TimeSpan) | Sets the current object to the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [operator-](./operator-/)(TimeSpan) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| [operator-](./operator-/)(DateTime) const | Returns an instance of [TimeSpan](../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects. |
| [operator-=](./operator-=/)(TimeSpan) | Sets the current object to the date and time value that is the result of subtraction of the specified time span from the date and time value represented by the current object. |
| [operator<](./operator_/)(DateTime) const | Determines if the current object represents the date and time value that is earlier than the value represented by the specified [DateTime](./) object. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(DateTime) const | Determines if the current object represents the date and time value that is earlier than or the same as the value represented by the specified [DateTime](./) object. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const DateTime\&) | Assigns the value represented by the specified [DateTime](./) instance to the current object. |
| [operator==](./operator==/)(DateTime) const | Determines if the current object and the specified [DateTime](./) object represent the same date and time value. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(DateTime) const | Determines if the current object represents the date and time value that is later than the value represented by the specified [DateTime](./) object. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(DateTime) const | Determines if the current object represents the date and time value that is later than or the same as the value represented by the specified [DateTime](./) object. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using culture-specific format information. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified format and culture-specific format information. The format of the string representation must match the specified format exactly. Throws an exception if the conversion fails. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified formats, culture-specific format information and style. The format of the string representation must match one or more of the specified formats exactly. Throws an exception if the conversion fails. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) |  |
| static [SpecifyKind](./specifykind/)(DateTime, DateTimeKind) | Constructs a new [DateTime](./) object that represents the same number of ticks as the specified [DateTime](./) object and represents local time, UTC time or neither as specified by the argument **kind**. |
| [Subtract](./subtract/)(TimeSpan) const | Returns a new instance of the [DateTime](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| [Subtract](./subtract/)(DateTime) const | Returns an instance of [TimeSpan](../timespan/) class representing the time interval between the date and time values represented by the current and the specified objects. |
| [ToBinary](./tobinary/)() const | Serializes the current object. |
| [ToFileTime](./tofiletime/)() const | Returns a value that represents the date and time value represented by the current object as File time. |
| [ToFileTimeUtc](./tofiletimeutc/)() const | Converts the date and time value represented by the current object to File time UTC. |
| [ToLocalTime](./tolocaltime/)() const | Returns a new instance of [DateTime](./) class that represents the date and time value represented by the current object as local time. |
| [ToLongDateString](./tolongdatestring/)() const | Returns a string that contains the long date string representation of the current object. |
| [ToLongTimeString](./tolongtimestring/)() const | Returns a string that contains the long time string representation of the current object. |
| [ToOADate](./tooadate/)() const | Returns the date and time value represented by the current object as OLE Automation Date. |
| [ToShortDateString](./toshortdatestring/)() const | Returns a string that contains the short date string representation of the current object. |
| [ToShortTimeString](./toshorttimestring/)() const | Returns a string that contains the short time string representation of the current object. |
| [ToString](./tostring/)() const | Returns the string representation of the date and time value represented by the current object using the formatting conventions defined by the current culture. |
| [ToString](./tostring/)(const String\&) const | Returns a string representation of the date and time value represented by the current object using the specified format and formatting conventions defined by the current culture. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Returns a string representation of the date and time value represented by the current object using the specified format information. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Returns a string representation of the date and time value represented by the current object using the specified format information. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToUniversalTime](./touniversaltime/)() const | Returns a new instance of [DateTime](./) class that represents the date and time value represented by the current object as UTC. |
| [ToUnixTime](./tounixtime/)() const | Returns a value that represents the date and time value represented by the current object as Unix time. FOR INTERNAL USE. |
| static [TryParse](./tryparse/)(const String\&, DateTime\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified culture-specific format information and style. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified format, culture-specific format information and style. The format of the string representation must match the specified format exactly. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) | Converts the specified string representation of a date and time value to the equivalent [DateTime](./) object using the specified formats, culture-specific format information and style. The format of the string representation must match one or more of the specified formats exactly. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) |  |
| static [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that contains information about this class. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | The number of 100-nanosecond in the time interval between the minimal possible and maximal possible [DateTime](./) value. |
| static [MaxValue](./maxvalue/) | An instance of [DateTime](./) class that represents the maximal possible date and time value. |
| static constexpr [MinTicks](./minticks/) | The minimal number of ticks that an instance of [DateTime](./) class can represent. |
| static [MinValue](./minvalue/) | An instance of [DateTime](./) class that represents the minimal possible date and time value. |
| static constexpr [TicksPerDay](./ticksperday/) | The number of ticks in a day. |
| static constexpr [TicksPerHour](./ticksperhour/) | The number of ticks in a hour. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | The number of ticks in a microsecond. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | The number of ticks in a millisecond. |
| static constexpr [TicksPerMinute](./ticksperminute/) | The number of ticks in a minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | The number of ticks in a second. |
| static [UnixEpoch](./unixepoch/) | An instance of [DateTime](./) class that represents the Unix epoch start (1970.01.01 00:00:00). |
## Remarks



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Create the 'DateTime' class instance.
  DateTime dateTime{1990, 10, 30};

  // Print the instance in the multiple formats.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
This code example produces the following output:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
