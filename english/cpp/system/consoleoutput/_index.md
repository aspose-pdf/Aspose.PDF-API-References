---
title: System::ConsoleOutput class
linktitle: ConsoleOutput
second_title: Aspose.PDF for C++ API Reference
description: 'System::ConsoleOutput class. Represents the standard output stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1500
url: /cpp/system/consoleoutput/
---
## ConsoleOutput class


Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Always returns ASCII encoding. |
| [Write](./write/)(bool) override | Outputs the string representation of the specified bool value to the output stream represented by the current object. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Outputs the string representation of the specified object to the output stream represented by the current object. |
| [Write](./write/)(char_t) override | Outputs the specified character value to the output stream represented by the current object. |
| [Write](./write/)(Decimal) override | Outputs the string representation of [Decimal](../decimal/) value to the output stream represented by the current object. |
| [Write](./write/)(double) override | Outputs the string representation of double-precision floating-point value to the output stream represented by the current object. |
| [Write](./write/)(int32_t) override | Outputs the string representation of 32-bit integer value to the output stream represented by the current object. |
| [Write](./write/)(int64_t) override | Outputs the string representation of 64-bit integer value to the output stream represented by the current object. |
| [Write](./write/)(float) override | Outputs the string representation of single-precision floating-point value to the output stream represented by the current object. |
| [Write](./write/)(const String\&) override | Outputs the specified string object to the output stream represented by the current object. |
| [Write](./write/)(uint32_t) override | Outputs the string representation of unsigned 32-bit integer value to the output stream represented by the current object. |
| [Write](./write/)(uint64_t) override | Outputs the string representation of unsigned 64-bit integer value to the output stream represented by the current object. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Outputs the string representation of the specified character array to the output stream represented by the current object. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Outputs the string representation of a range of values of the specified character array to the output stream represented by the current object. |
| [Write](./write/)(const char_t *) override | Outputs the specified c-string to the output stream represented by the current object. |
| [Write](./write/)(const TypeInfo\&) override | Outputs the string representation of the specified [TypeInfo](../typeinfo/) object to the output stream represented by the current object. |
| [Write](./write/)(const char *) |  |
| [WriteLine](./writeline/)() override | Outputs the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Outputs the string representation of the specified object followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(bool) override | Outputs the string representation of the specified bool value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(char_t) override | Outputs the specified character value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(Decimal) override | Outputs the string representation of [Decimal](../decimal/) value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(double) override | Outputs the string representation of double-precision floating-point value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(int) override | Outputs the string representation of 32-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(int64_t) override | Outputs the string representation of 64-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(float) override | Outputs the string representation of single-precision floating-point value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const String\&) override | Outputs the specified string object followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(uint32_t) override | Outputs the string representation of unsigned 32-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(uint64_t) override | Outputs the string representation of unsigned 64-bit integer value followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Outputs the string representation of the specified character array followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Outputs the string representation of a range of values of the specified character array followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const char_t *) override | Outputs the specified c-string followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const TypeInfo\&) override | Outputs the string representation of the specified [TypeInfo](../typeinfo/) object followed by the current line terminator to the output stream represented by the current object. |
| [WriteLine](./writeline/)(const char *) |  |
## See Also

* Class [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
