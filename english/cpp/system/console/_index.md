---
title: System::Console class
linktitle: Console
second_title: Aspose.PDF for C++ API Reference
description: 'System::Console class. Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1400
url: /cpp/system/console/
---
## Console class


Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Console
```

## Methods

| Method | Description |
| --- | --- |
| static [Beep](./beep/)() | NOT IMPLEMENTED. |
| static [get_Error](./get_error/)() | Returns a shared pointer pointing to the object that represents the standard error stream. |
| static [get_In](./get_in/)() | Returns a shared pointer pointing to the object that represents the standard input stream. |
| static [get_Out](./get_out/)() | Returns a shared pointer pointing to the object that represents the standard output stream. |
| static [Mute](./mute/)(bool) | Mutes or unmutes the standard output stream. |
| static [ReadKey](./readkey/)() | NOT IMPLEMENTED. |
| static [SetError](./seterror/)(const SharedPtr\<System::IO::TextWriter\>\&) | Assigns the specified object to the class' Error property. |
| static [SetIn](./setin/)(const SharedPtr\<System::IO::TextReader\>\&) | Sets the In property to the specified TextReader object. |
| static [SetOut](./setout/)(const SharedPtr\<System::IO::TextWriter\>\&) | Assigns the specified object to the class' Out property. |
| static [Write](./write/)(const SharedPtr\<T\>\&) | Outputs the string representation of the specified object to the standard output stream. |
| static [Write](./write/)(bool) | Outputs the string representation of bool value to the standard output stream. |
| static [Write](./write/)(char_t) | Outputs the specified character value to the standard output stream. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&) | Outputs the string representation of the specified character array to the standard output stream. |
| static [Write](./write/)(const Decimal\&) | Outputs the string representation of [Decimal](../decimal/) value to the standard output stream. |
| static [Write](./write/)(double) | Outputs the string representation of double-precision floating-point value to the standard output stream. |
| static [Write](./write/)(float) | Outputs the string representation of single-precision floating-point value to the standard output stream. |
| static [Write](./write/)(int32_t) | Outputs the string representation of 32-bit integer value to the standard output stream. |
| static [Write](./write/)(int64_t) | Outputs the string representation of 64-bit integer value to the standard output stream. |
| static [Write](./write/)(const String\&) | Outputs the specified string object to the standard output stream. |
| static [Write](./write/)(const char_t *) | Outputs the specified c-string to the standard output stream. |
| static [Write](./write/)(const TypeInfo\&) | Outputs the string representation of [TypeInfo](../typeinfo/) value to the standard output stream. |
| static [Write](./write/)(uint32_t) | Outputs the string representation of unsigned 32-bit integer value to the standard output stream. |
| static [Write](./write/)(uint64_t) | Outputs the string representation of unsigned 64-bit integer value to the standard output stream. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Outputs the string representation of the specified range of the specified character array to the standard output stream. |
| static [Write](./write/)(const String\&, Args\&&...) | Outputs the string representation of the specified arguments formatted according to the specified format to the standard output stream. |
| static [Write](./write/)(const char *) |  |
| static [WriteLine](./writeline/)() | Outputs the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const SharedPtr\<T\>\&) | Outputs the string representation of the specified object followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(bool) | Outputs the string representation of bool value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(char_t) | Outputs the specified character value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Outputs the string representation of the specified character array followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const Decimal\&) | Outputs the string representation of [Decimal](../decimal/) value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(double) | Outputs the string representation of double-precision floating-point value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(float) | Outputs the string representation of single-precision floating-point value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(int32_t) | Outputs the string representation of 32-bit integer value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(int64_t) | Outputs the string representation of 64-bit integer value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const String\&) | Outputs the specified string object followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const char_t *) | Outputs the specified c-string followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const TypeInfo\&) | Outputs the string representation of [TypeInfo](../typeinfo/) value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(uint32_t) | Outputs the string representation of unsigned 32-bit integer value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(uint64_t) | Outputs the string representation of unsigned 64-bit integer value followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int, int) | Outputs the string representation of the specified range of the specified character array followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const Exception\&) | Outputs the string representation of the specified [Exception](../exception/) object followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const String\&, Args\&&...) | Outputs the string representation of the specified arguments formatted according to the specified format followed by the current line terminator to the standard output stream. |
| static [WriteLine](./writeline/)(const char *) |  |
## Remarks



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Print the hello message.
  Console::WriteLine(u"Hello, world!");

  // Create an instance of the 'std::array' class.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Print elements of the array.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
1 2 3 4 5
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
