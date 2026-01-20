---
title: System::TimeSpan class
linktitle: TimeSpan
second_title: Aspose.PDF for C++ API Reference
description: 'System::TimeSpan class. Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 6100
url: /cpp/system/timespan/
---
## TimeSpan class


Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TimeSpan
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the sum of the time intervals represented by the current and the specified objects. |
| static [Compare](./compare/)(TimeSpan, TimeSpan) | Compares two [TimeSpan](./) objects. |
| [CompareTo](./compareto/)(TimeSpan) const | Compares current and the specified objects. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Compares current and the specified objects. |
| [Duration](./duration/)() const | Returns a new instance of [TimeSpan](./) object whose value is the absolute value of the current object. |
| [Equals](./equals/)(TimeSpan) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| static [Equals](./equals/)(TimeSpan, TimeSpan) | Returns true if the specified objects represent the same time interval, otherwise - false. |
| static [FromDays](./fromdays/)(double) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [FromHours](./fromhours/)(double) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [FromMilliseconds](./frommilliseconds/)(double) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [FromMinutes](./fromminutes/)(double) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [FromSeconds](./fromseconds/)(double) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| static [FromTicks](./fromticks/)(int64_t) | Returns a new [TimeSpan](./) object that represents the specified interval. |
| [get_Days](./get_days/)() const | Returns the days component of the time interval represented by the current [TimeSpan](./) object. |
| [get_Hours](./get_hours/)() const | Returns the hours component of the time interval represented by the current [TimeSpan](./) object. |
| [get_Milliseconds](./get_milliseconds/)() const | Returns the milliseconds component of the time interval represented by the current [TimeSpan](./) object. |
| [get_Minutes](./get_minutes/)() const | Returns the minutes component of the time interval represented by the current [TimeSpan](./) object. |
| [get_Seconds](./get_seconds/)() const | Returns the seconds component of the time interval represented by the current [TimeSpan](./) object. |
| [get_Ticks](./get_ticks/)() const | Returns the number of 100-nanoseconds intervals that constitute the time interval represented by the current [TimeSpan](./) object. |
| [get_TotalDays](./get_totaldays/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional days. |
| [get_TotalHours](./get_totalhours/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional hours. |
| [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional milliseconds. |
| [get_TotalMinutes](./get_totalminutes/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional minutes. |
| [get_TotalSeconds](./get_totalseconds/)() const | Returns the value of the current [TimeSpan](./) object expressed in whole and fractional seconds. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [IsNull](./isnull/)() const |  |
| [Negate](./negate/)() const | Returns a new instance of [TimeSpan](./) object that represents negated value represented by the current [TimeSpan](./) object. |
| [operator!=](./operator!=/)(TimeSpan) const | Determines if the time interval represented by the current object is not equal to the time interval represented by the specified object. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the sum of the time intervals represented by the current and the specified objects. |
| [operator+](./operator+/)() const | Returns self. |
| [operator+=](./operator+=/)(TimeSpan) | Assigns to the current object the time interval which is the sum of the time interval represented by the current and the specified objects. |
| [operator-](./operator-/)(TimeSpan) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| [operator-](./operator-/)() const | Returns a new instance of [TimeSpan](./) object that represents negated value represented by the current [TimeSpan](./) object. |
| [operator-=](./operator-=/)(TimeSpan) | Assigns to the current object the time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| [operator/](./operator//)(double) const |  |
| [operator/](./operator//)(TimeSpan) const |  |
| [operator/=](./operator/=/)(double) |  |
| [operator<](./operator_/)(TimeSpan) const | Determines if the time interval represented by the current object is shorter than the time interval represented by the specified object. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(TimeSpan) const | Determines if the time interval represented by the current object is shorter than or equal to the time interval represented by the specified object. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const TimeSpan\&) | Sets the time interval represented by the specified [TimeSpan](./) object to the current [TimeSpan](./) object. |
| [operator==](./operator==/)(TimeSpan) const | Determines if the time interval represented by the current object is equal to the time interval represented by the specified object. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(TimeSpan) const | Determines if the time interval represented by the current object is longer than the time interval represented by the specified object. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(TimeSpan) const | Determines if the time interval represented by the current object is longer than or equal to the time interval represented by the specified object. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Converts string to equivalent [TimeSpan](./) object. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Converts string to equivalent [TimeSpan](./) object using the specified format provider. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Converts string to equivalent [TimeSpan](./) object using the specified formats, format provider and styles. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Converts string to equivalent [TimeSpan](./) object using the specified format, format provider and styles. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| [Subtract](./subtract/)(TimeSpan) const | Returns a new instance of [TimeSpan](./) class that represents a time interval which is the result of subtraction of the time interval represented by the specified object from the time interval represented by the current object. |
| [TimeSpan](./timespan/)() | Constructs a [TimeSpan](./) object that represents a zero time interval. |
| explicit [TimeSpan](./timespan/)(int64_t) | Constructs an instance of [TimeSpan](./) class that represents the specified time interval. |
| [TimeSpan](./timespan/)(int, int, int) | Constructs an instance of [TimeSpan](./) class that represents the time interval which is equal to the sum of the specified number of hours, minutes and seconds. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Constructs an instance of [TimeSpan](./) class that represents the time interval which is equal to the sum of the specified number of hours, minutes, seconds and milliseconds. |
| [TimeSpan](./timespan/)(const TimeSpan\&) | Constructs a [TimeSpan](./) object that represents the time interval equal to the time interval represented by the specified [TimeSpan](./) object. |
| [ToString](./tostring/)() const | Returns the string representation of the time interval represented by the current object. |
| [ToString](./tostring/)(const String\&) const | Converts the value of the current object to equivalent string representation, using the specified format. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Converts the value of the current object to equivalent string representation, using the specified format and format provider. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| static [TryParse](./tryparse/)(const String\&, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object and returns result of conversion. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object using the specified format provider and returns result of conversion. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object using the specified formats and format provider, and returns result of conversion. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object using the specified format, format provider and styles, and returns result of conversion. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object using the specified formats, format provider and styles, and returns result of conversion. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Converts string to equivalent [TimeSpan](./) object using the specified format and format provider, and returns result of conversion. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [Type](./type/)() | Returns a [TypeInfo](../typeinfo/) object that represent [TimeSpan](./) structure. |
## Fields

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | The [TimeSpan](./) object that represents the longest possible interval. |
| static [MinValue](./minvalue/) | /// The [TimeSpan](./) object that represents the shortest possible interval. |
| static constexpr [TicksPerDay](./ticksperday/) | The number of 100-nanoseconds intervals in a day (24-hour interval). |
| static constexpr [TicksPerHour](./ticksperhour/) | The number of 100-nanoseconds intervals in a hour. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | The number of 100-nanoseconds intervals in a millisecond. |
| static constexpr [TicksPerMinute](./ticksperminute/) | The number of 100-nanoseconds intervals in a minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | The number of 100-nanoseconds intervals in a second. |
| static [Zero](./zero/) | The [TimeSpan](./) object that represents zero-interval. |
## Remarks



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
