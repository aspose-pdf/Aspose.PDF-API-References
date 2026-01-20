---
title: System::IO::BinaryWriter class
linktitle: BinaryWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryWriter class. Represents a writer that writes values of primitive types to a byte stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.io/binarywriter/
---
## BinaryWriter class


Represents a writer that writes values of primitive types to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [BinaryWriter](./binarywriter/)(const StreamPtr\&, const EncodingPtr\&, bool) | Constructs an instance of [BinaryWriter](./) class that writes data to the specified stream using the specified encoding. |
| [Close](./close/)() | Closes the current [BinaryWriter](./) object and the underlying output stream. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| [Flush](./flush/)() | Flushes the output stream. |
| [get_BaseStream](./get_basestream/)() | Returns the output stream. |
| [Seek](./seek/)(int, System::IO::SeekOrigin) | Sets the position of the stream represented by the current object. |
| virtual [Write](./write/)(uint8_t) | Writes the specified unsigned 8-bit integer value to the output stream. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int, int) | Writes the specified subrange of bytes from the specified byte array to the output stream. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int, int) | Writes the specified subrange of UTF-16 characters from the specified character array to the output stream. |
| virtual [Write](./write/)(bool) | Writes single byte with a value of 0 if **value** is 'true' and 1 if **value** is 'false' to the output stream. |
| virtual [Write](./write/)(char16_t) | Writes the specified 16-bit wide character value to the output stream. |
| virtual [Write](./write/)(int16_t) | Writes the specified 16-bit integer value to the output stream. |
| virtual [Write](./write/)(int) | Writes the specified 32-bit integer value to the output stream. |
| virtual [Write](./write/)(int64_t) | Writes the specified 64-bit integer value to the output stream. |
| virtual [Write](./write/)(uint16_t) | Writes the specified unsigned 16-bit integer value to the output stream. |
| virtual [Write](./write/)(uint32_t) | Writes the specified unsigned 32-bit integer value to the output stream. |
| virtual [Write](./write/)(uint64_t) | Writes the specified unsigned 64-bit integer value to the output stream. |
| virtual [Write](./write/)(float) | Writes the specified single-precision floating point value to the output stream. |
| virtual [Write](./write/)(double) | Writes the specified double-precision floating point value to the output stream. |
| virtual [Write](./write/)(const Decimal\&) | Writes the byte representation of the specified [Decimal](../../system/decimal/) value to the output stream. |
| virtual [Write](./write/)(const String\&) | Writes a length-prefixed string in the current encoding to the output stream. |
| virtual [Write](./write/)(const char_t *) | Writes a length-prefixed string in the current encoding to the output stream. |
| [~BinaryWriter](./~binarywriter/)() | Destructor. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
