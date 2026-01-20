---
title: System::Guid class
linktitle: Guid
second_title: Aspose.PDF for C++ API Reference
description: 'System::Guid class. Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 3000
url: /cpp/system/guid/
---
## Guid class


Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Guid
```

## Methods

| Method | Description |
| --- | --- |
| [CompareTo](./compareto/)(const Guid\&) const | Performs arithmetic comparison of the GUIDs represented by the current and specified objects. |
| [Equals](./equals/)(const Guid\&) const | Determines if the GUIDs represented by the current and specified objects are equal. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [Guid](./guid/)() | Constructs an object that represents a GUID consisting of all zeroes. |
| [Guid](./guid/)(const ArrayPtr\<uint8_t\>\&) | Constructs an object that represents a GUID specified as an array of unsigned 8-bit integer values. |
| [Guid](./guid/)(const System::Details::ArrayView\<uint8_t\>\&) | Constructs an object that represents a GUID specified as an array view of unsigned 8-bit integer values. |
| [Guid](./guid/)(const String\&) | Constructs an object that represents a GUID specified as a string. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) | Constructs an instance of [Guid](./) class from the specified GUID components. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) | Constructs an instance of [Guid](./) class from the specified GUID components. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Constructs an instance of [Guid](./) class from the specified unsigned integers and bytes. |
| [Guid](./guid/)(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Constructs an instance of [Guid](./) class from the specified unsigned integers and bytes. |
| [Guid](./guid/)(const Guid\&) | Constructs an object that represents the same GUID as the specified object. |
| static [NewGuid](./newguid/)() | Generates a new GUID and returns a [Guid](./) object that represents it. |
| [operator!=](./operator!=/)(const Guid\&) const | Determines if the GUIDs represented by the current and specified objects are not equal. |
| [operator=](./operator=/)(const Guid\&) | Assigns to the current object the GUID value represented by the specified [Guid](./) object. |
| [operator==](./operator==/)(const Guid\&) const | Determines if the GUIDs represented by the current and specified objects are equal. |
| static [Parse](./parse/)(const String\&) | Converts the specified string representation of a GUID into equivalent [Guid](./) object. |
| [ToByteArray](./tobytearray/)() const | Converts the GUID represented by the current object into array of bytes. |
| [ToString](./tostring/)() const | Converts the GUID represented by the current object to its string representation. |
| [ToString](./tostring/)(const String\&) const | Converts the GUID represented by the current object to its string representation using the specified string format. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const | Converts the GUID represented by the current object to its string representation using the specified string format and Culture. |
| static [TryParse](./tryparse/)(const String\&, Guid\&) | Tries to convert the specified string into [Guid](./) object. |
| [~Guid](./~guid/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Represents a GUID that has a value of 0. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
