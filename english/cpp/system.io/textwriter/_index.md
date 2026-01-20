---
title: System::IO::TextWriter class
linktitle: TextWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextWriter class. A base class for classes that represent writers that writes sequences of characters to different destinations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.io/textwriter/
---
## TextWriter class


A base class for classes that represent writers that writes sequences of characters to different destinations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | Closes the stream and releases aquired resources. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual [Flush](./flush/)() | Flushes the content of the buffer to the underlying stream. |
| virtual [get_Encoding](./get_encoding/)() | Returns the currently used encoding. |
| virtual [get_FormatProvider](./get_formatprovider/)() const | Returns the currently used [IFormatProvider](../../system/iformatprovider/) object. |
| [get_FormatProvider](./get_formatprovider/)() | Returns the currently used [IFormatProvider](../../system/iformatprovider/) object. |
| virtual [get_NewLine](./get_newline/)() const | Returns a line terminator string. |
| [get_NewLine](./get_newline/)() | Returns a line terminator string. |
| virtual [set_NewLine](./set_newline/)(const System::String\&) | Sets a line terminator string. |
| virtual [Write](./write/)(const SharedPtr\<Object\>\&) | Writes the string representation of the specified object to the stream. |
| virtual [Write](./write/)(bool) | Writes the string representation of the specified boolean value to the stream. |
| virtual [Write](./write/)(char_t) | Writes the specified character to the stream. |
| virtual [Write](./write/)(Decimal) | Writes the string representation of the specified [Decimal](../../system/decimal/) object to the stream. |
| virtual [Write](./write/)(double) | Writes the string representation of the specified double-precision floating point value to the stream. |
| virtual [Write](./write/)(int) | Writes the string representation of the specified 32-bit integer value to the stream. |
| virtual [Write](./write/)(int64_t) | Writes the string representation of the specified 64-bit integer value to the stream. |
| virtual [Write](./write/)(float) | Writes the string representation of the specified single-precision floating point value to the stream. |
| virtual [Write](./write/)(const String\&) | Writes the specified string to the stream. |
| virtual [Write](./write/)(uint32_t) | Writes the string representation of the specified unsigned 32-bit integer value to the stream. |
| virtual [Write](./write/)(uint64_t) | Writes the string representation of the specified unsigned 64-bit integer value to the stream. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&) | Writes all characetrs from the specified array to the stream. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Writes the specified subrange of UTF-16 characters from the specified character array to the stream. |
| virtual [Write](./write/)(const char_t *) | Writes the specified c-string to the stream. |
| virtual [Write](./write/)(const TypeInfo\&) | Writes the string representation of the specified [TypeInfo](../../system/typeinfo/) object to the stream. |
| [Write](./write/)(const String\&, const TArgs\&...) | Writes the specified values formatted according to the specified format to the stream. |
| virtual [WriteLine](./writeline/)() | Writes line terminator characters to the stream. |
| virtual [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) | Writes the string representation of the specified object followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(bool) | Writes the string representation of the specified boolean value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(char_t) | Writes the specified character followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(Decimal) | Writes the string representation of the specified [Decimal](../../system/decimal/) object followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(double) | Writes the string representation of the specified double-precision floating point value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(int) | Writes the string representation of the specified 32-bit integer value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(int64_t) | Writes the string representation of the specified 64-bit integer value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(float) | Writes the string representation of the specified single-precision floating point value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(const String\&) | Writes the specified string followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(uint32_t) | Writes the string representation of the specified unsigned 32-bit integer value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(uint64_t) | Writes the string representation of the specified unsigned 64-bit integer value followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Writes all characetrs from the specified array followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Writes the specified subrange of UTF-16 characters from the specified character array followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(const char_t *) | Writes the specified c-string followed by the line-terminating characters to the stream. |
| virtual [WriteLine](./writeline/)(const TypeInfo\&) | Writes the string representation of the specified [TypeInfo](../../system/typeinfo/) object followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const String\&, const TArgs\&...) | Writes the specified values formatted according to the specified format followed by the line-terminating characetrs to the stream. |
| virtual [~TextWriter](./~textwriter/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for a shared pointer to this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
