---
title: System::Decimal class
linktitle: Decimal
second_title: Aspose.PDF for C++ API Reference
description: 'System::Decimal class. Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 1900
url: /cpp/system/decimal/
---
## Decimal class


Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Decimal
```

## Methods

| Method | Description |
| --- | --- |
| static [Add](./add/)(const Decimal\&, const Decimal\&) | Adds two specified [Decimal](./) values. |
| static [Ceiling](./ceiling/)(const Decimal\&) | Returns the smallest integral value that is greater than or equal to the specified value. |
| static [Compare](./compare/)(const Decimal\&, const Decimal\&) | Determines if the value represented by the first [Decimal](./) object is less than, equal to or greater than the value represented by the second [Decimal](./) object. |
| [CompareTo](./compareto/)(const Decimal\&) const | Determines if the value represented by the current object is less than, equal to or greater than the value represented by the specified object. |
| [Decimal](./decimal/)() | Constructs an instance that represents 0. |
| [Decimal](./decimal/)(std::int8_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::int16_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::int32_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::int64_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::uint8_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::uint16_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::uint32_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(std::uint64_t) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(float) | Constructs an instance that represents the specified value. |
| [Decimal](./decimal/)(double) | Constructs an instance that represents the specified value. |
| explicit [Decimal](./decimal/)(const std::string\&) | Constructs an instance that represents a value whose string representation is specified as an instance of std::string class. |
| [Decimal](./decimal/)(int32_t, int32_t, int32_t, bool, uint8_t) | Constructs a [Decimal](./) object from the specified from the specified components. |
| [Decimal](./decimal/)(const Decimal\&) | Constructs an instance of [Decimal](./) class that represents the same number as the specified [Decimal](./) object. |
| [Decimal](./decimal/)(const ArrayPtr\<int32_t\>\&) | Constructs an instance of [Decimal](./) class from integer array containing a binary representation. |
| [Decimal](./decimal/)(std::nullptr_t) | Always throws ArgumentNullException. |
| [Decimal](./decimal/)(const number_type\&) | Constructs an instance of [Decimal](./) class representing the specified value. |
| static [Divide](./divide/)(const Decimal\&, const Decimal\&) | Divides two specified [Decimal](./) values. |
| [Equals](./equals/)(const Decimal\&) const | Determines if the values represented by the current object and the specified object are equal. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Determines if the values represented by the current object and the specified object are equal. |
| static [Equals](./equals/)(const Decimal\&, const Decimal\&) | Determines if the values represented by the specified objects are equal. |
| static [Floor](./floor/)(const Decimal\&) | Returns the largest integral value that is less than or equal to the specified value. |
| static [FromOACurrency](./fromoacurrency/)(int64_t) | [Convert](../convert/) the specified OLE currency value to the equivalent [Decimal](./) value. NOT IMPLEMENTED. |
| static [GetBits](./getbits/)(const Decimal\&) | Converts the specified [Decimal](./) object into the binary representation of the value it represents. |
| static [GetBytes](./getbytes/)(const Decimal\&, const System::ArrayPtr\<uint8_t\>\&) | [Convert](../convert/) the specified [Decimal](./) value to an array of bytes. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [GetTypeCode](./gettypecode/)() const | Gets object type code. |
| static [Multiply](./multiply/)(const Decimal\&, const Decimal\&) | Multiplies two specified [Decimal](./) values. |
| static [Negate](./negate/)(const Decimal\&) | Returns a new instance of [Decimal](./) class that represents a value that results from negation of the value represented by the specified object. |
| explicit [operator bool](./operatorbool/)() const | Converts the value represented by the current object to a boolean value. |
| explicit [operator double](./operatordouble/)() const | Converts the value represented by the current object to double-precision floating-point value. |
| explicit [operator float](./operatorfloat/)() const | Converts the value represented by the current object to single-precision floating-point value. |
| [operator!=](./operator!=/)(const Decimal\&) const | Determines if the values represented by the current object and the specified object are not equal. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determines if the value represented by the current object is different from 0. |
| [operator%](./operator-percent/)(const Decimal\&) const | Returns a new instance of [Decimal](./) class that represents a value that is a result of modulo operation with the values represented by the current and the specified objects. |
| [operator%=](./operator-percent-equal/)(const Decimal\&) | Assigns to the current object a new value that is the result of modulo operation with the values represented by the current and the specified objects. |
| [operator*](./operator_/)(const Decimal\&) const | Returns a new instance of [Decimal](./) class that represents a value that is a result of multiplication of values represented by the current and specified objects. |
| [operator*=](./operator_=/)(const Decimal\&) | Assigns to the current object a new value that is the result of multiplication of values represented by the current and specified objects. |
| [operator+](./operator+/)(const Decimal\&) const | Returns a new instance of [Decimal](./) class that represents a value that is a sum of values represented by the current and specified objects. |
| [operator++](./operator++/)() | Increments the value represented by the current object. |
| [operator+=](./operator+=/)(const Decimal\&) | Assigns to the current object a new value that is a sum of values represented by the current and specified objects. |
| [operator-](./operator-/)(const Decimal\&) const | Returns a new instance of [Decimal](./) class that represents a value that is the result of subtraction of the value represented by the specified object from the value represented by the current object. |
| [operator-](./operator-/)() const | Returns a new instance of [Decimal](./) class that represents a value that results from negation of the value represented by the current object. |
| [operator--](./operator--/)() | Decrements the value represented by the current object. |
| [operator-=](./operator-=/)(const Decimal\&) | Assigns to the current object a new value that is the result of subtraction of the value represented by the specified object from the value represented by the current object. |
| [operator/](./operator//)(const Decimal\&) const | Returns a new instance of [Decimal](./) class that represents a value that is a result of division of the value represented by the current object by the value represented by the specified object. |
| [operator/=](./operator/=/)(const Decimal\&) | Assigns to the current object a new value that is the result of division of the value represented by the current object by the value represented by the specified object. |
| [operator<](./operator_/)(const Decimal\&) const | Determines if the value represented by the current object is less than the value represented by the specified object. |
| [operator<=](./operator_=/)(const Decimal\&) const | Determines if the value represented by the current object is less than or equal to the value represented by the specified object. |
| [operator=](./operator=/)(const Decimal\&) | Assigns the value represented by the specified object to the current object. |
| [operator==](./operator==/)(const Decimal\&) const | Determines if the values represented by the current object and the specified object are equal. |
| [operator==](./operator==/)(std::nullptr_t) const | Determines if the value represented by the current object is 0. |
| [operator>](./operator_/)(const Decimal\&) const | Determines if the value represented by the current object is greater than the value represented by the specified object. |
| [operator>=](./operator_=/)(const Decimal\&) const | Determines if the value represented by the current object is greater than or equal to the value represented by the specified object. |
| static [Parse](./parse/)(const String\&) | Converts the string representation of a decimal number into an equivalent instance of [Decimal](./) class. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles) | Converts the string representation of a decimal number into an equivalent instance of [Decimal](./) class using the specified style. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Converts the string representation of a decimal number into an equivalent instance of [Decimal](./) class using the specified format provider. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Converts the string representation of a decimal number into an equivalent instance of [Decimal](./) class using the specified style and format provider. |
| static [Remainder](./remainder/)(const Decimal\&, const Decimal\&) | Computes the remainder after dividing two [Decimal](./) values. |
| static [Round](./round/)(const Decimal\&, MidpointRounding) | Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static [Round](./round/)(const Decimal\&, int, MidpointRounding) | Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static [Subtract](./subtract/)(const Decimal\&, const Decimal\&) | Subtracts one specified [Decimal](./) value from another. |
| static [ToByte](./tobyte/)(Decimal) | Converts the [Decimal](./) value to unsigned 8-bit integer value. |
| static [ToDouble](./todouble/)(Decimal) | Converts the [Decimal](./) value to double precision floating-point number. |
| static [ToInt16](./toint16/)(Decimal) | Converts the [Decimal](./) value to signed 16-bit integer value. |
| static [ToInt32](./toint32/)(Decimal) | Converts the [Decimal](./) value to signed 32-bit integer value. |
| static [ToInt64](./toint64/)(Decimal) | Converts the [Decimal](./) value to signed 64-bit integer value. |
| static [ToOACurrency](./tooacurrency/)(const Decimal\&) | [Convert](../convert/) the specified [Decimal](./) value to the equivalent OLE currency value. NOT IMPLEMENTED. |
| static [ToSByte](./tosbyte/)(Decimal) | Converts the [Decimal](./) value to signed 8-bit integer value. |
| static [ToSingle](./tosingle/)(Decimal) | Converts the [Decimal](./) value to single precision floating-point number. |
| [ToStdString](./tostdstring/)() const | Returns an instance of std::string that contains the string representation of the value represented by the object. |
| [ToString](./tostring/)() const | Returns the string representation of the value represented by the object. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Converts current object to string using the culture-specific format information. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const Decimal\&, std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Converts current object to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToStringInternal](./tostringinternal/)() const | Returns the string representation of the value represented by the object. For internal use. |
| static [ToUInt16](./touint16/)(Decimal) | Converts the [Decimal](./) value to unsigned 16-bit integer value. |
| static [ToUInt32](./touint32/)(Decimal) | Converts the [Decimal](./) value to unsigned 32-bit integer value. |
| static [ToUInt64](./touint64/)(Decimal) | Converts the [Decimal](./) value to unsigned 64-bit integer value. |
| static [Truncate](./truncate/)(const Decimal\&) | Returns the [Decimal](./) object representing a value that has integral part equal to that of the value represented by the specified [Decimal](./) object of the with all fractional digits discarded. |
| static [TryParse](./tryparse/)(const String\&, Decimal\&) | Converts the specified string containing the string representation of a number to the equivalent [Decimal](./) value. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) | Converts the specified string containing the string representation of a number to the equivalent [Decimal](./) value using the provided formatting information and number style. |
| static [Type](./type/)() | Returns a reference to the [TypeInfo](../typeinfo/) object representing the [Decimal](./) class' type information. |
| [~Decimal](./~decimal/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Represents the largest number that can be represented by [Decimal](./) class. |
| static [MinusOne](./minusone/) | Represents number -1. |
| static [MinValue](./minvalue/) | Represents the smallest number that can be represented by [Decimal](./) class. |
| static [One](./one/) | Represents number 1. |
| static [Zero](./zero/) | Represents number 0. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | An alias for Detail::decimal_number_type. |
## Remarks



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
This code example produces the following output:
-79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
