---
title: System::BitConverter class
linktitle: BitConverter
second_title: Aspose.PDF for C++ API Reference
description: 'System::BitConverter class. Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 500
url: /cpp/system/bitconverter/
---
## BitConverter class


Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class BitConverter
```

## Methods

| Method | Description |
| --- | --- |
| static [_IsLittleEndian](./_islittleendian/)() | Indicates the endianness of the current architecture. |
| static [DoubleToInt64Bits](./doubletoint64bits/)(double) | Returns a 64-bit integer value whose binary representation is equal to binary representation of the specified double-precision floating point value. |
| static [GetBytes](./getbytes/)(bool) | Converts the specified boolean value into an array of bytes. |
| static [GetBytes](./getbytes/)(char_t) | Converts the specified char_t value into an array of bytes. |
| static [GetBytes](./getbytes/)(int16_t) | Converts the specified 16-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(int) | Converts the specified 32-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(int64_t) | Converts the specified 64-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(uint16_t) | Converts the specified unsigned 16-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(uint32_t) | Converts the specified unsigned 32-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(uint64_t) | Converts the specified unsigned 64-bit integer value into an array of bytes. |
| static [GetBytes](./getbytes/)(float) | Converts the specified single-precision floating-point value into an array of bytes. |
| static [GetBytes](./getbytes/)(double) | Converts the specified double-precision floating-point value into an array of bytes. |
| static [Int64BitsToDouble](./int64bitstodouble/)(int64_t) | Returns a double-precision floating point value whose value is equivalent to value. |
| static [ToBoolean](./toboolean/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts one byte from the specified array starting at the specified index to boolean value. |
| static [ToBoolean](./toboolean/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts one byte from the specified array starting at the specified index to boolean value. |
| static [ToChar](./tochar/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to char_t value. |
| static [ToChar](./tochar/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to char_t value. |
| static [ToDouble](./todouble/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to double-precision floating point value. |
| static [ToDouble](./todouble/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to double-precision floating point value. |
| static [ToInt16](./toint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to 16-bit integer value. |
| static [ToInt16](./toint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to 16-bit integer value. |
| static [ToInt32](./toint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to 32-bit integer value. |
| static [ToInt32](./toint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to 32-bit integer value. |
| static [ToInt64](./toint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to 64-bit integer value. |
| static [ToInt64](./toint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to 64-bit integer value. |
| static [ToSingle](./tosingle/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to single-precision floating point value. |
| static [ToSingle](./tosingle/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to single-precision floating point value. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, bool, const String\&) | Converts all values of the specified byte array into their hexadecimal string representation. Case of letters to use in hexadecimal notation and separator inserted between each pair of neighbouring bytes are specified through corresponding arguments. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int) | Converts values of the specified byte array into their hexadecimal string representation starting at specified index. |
| static [ToString](./tostring/)(const ArrayPtr\<uint8_t\>\&, int, int) | Converts a range of values of the specified byte array into their hexadecimal string representation. |
| static [ToUInt16](./touint16/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to unsigned 16-bit integer value. |
| static [ToUInt16](./touint16/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts two bytes from the specified array starting at the specified index to unsigned 16-bit integer value. |
| static [ToUInt32](./touint32/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value. |
| static [ToUInt32](./touint32/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts four bytes from the specified array starting at the specified index to unsigned 32-bit integer value. |
| static [ToUInt64](./touint64/)(const System::ArrayPtr\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value. |
| static [ToUInt64](./touint64/)(const System::Details::ArrayView\<uint8_t\>\&, int) | Converts eight bytes from the specified array starting at the specified index to unsigned 64-bit integer value. |
## Fields

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indicates the endianness of the current architecture. true if the architecture is little endian, false otherwise. |
## Remarks



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Create values to print.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Print value and its bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
This code example produces the following output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
