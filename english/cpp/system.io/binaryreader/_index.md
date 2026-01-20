---
title: System::IO::BinaryReader class
linktitle: BinaryReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryReader class. Represents a reader that reads primitive data types as binary data in particular encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.io/binaryreader/
---
## BinaryReader class


Represents a reader that reads primitive data types as binary data in particular encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&) | Constructs an instance of [BinaryReader](./) class that reads data from the specified stream using UTF-8 encoding. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Constructs an instance of [BinaryReader](./) class that reads data from the specified stream using the specified encoding. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) | Constructs an instance of [BinaryReader](./) class that reads data from the specified stream using the specified encoding. |
| virtual [Close](./close/)() | Closes the current [BinaryReader](./) object and the underlying input stream. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual [get_BaseStream](./get_basestream/)() | Returns the input stream. |
| virtual [PeekChar](./peekchar/)() | Reads a single character from the input stream without changing the stream's read cursor. |
| virtual [Read](./read/)() | Reads a single character from the input stream. |
| virtual [Read](./read/)(ArrayPtr\<uint8_t\>, int, int) | Reads the specified number of bytes from the input stream and writes them to the specified byte array. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Reads the specified number of characters from the input stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position. |
| virtual [ReadBoolean](./readboolean/)() | Reads a single byte from the input stream and returns its boolean representation. |
| virtual [ReadByte](./readbyte/)() | Reads a single byte from the input stream. |
| virtual [ReadBytes](./readbytes/)(int) | Reads the specified number of bytes from the input stream. |
| virtual [ReadChar](./readchar/)() | Reads a single character from the input stream. |
| virtual [ReadChars](./readchars/)(int) | Reads the specified number of characters from the input stream and returns them in UTF-16 ecoding. |
| virtual [ReadDecimal](./readdecimal/)() | NOT IMPLEMENTED. |
| virtual [ReadDouble](./readdouble/)() | Reads 8 bytes from the input stream and returns them as a double-precision floating point value. |
| virtual [ReadInt16](./readint16/)() | Reads 2 bytes from the input stream and returns them as a 16-bit integer value. |
| virtual [ReadInt32](./readint32/)() | Reads 4 bytes from the input stream and returns them as a 32-bit integer value. |
| virtual [ReadInt64](./readint64/)() | Reads 8 bytes from the input stream and returns them as a 64-bit integer value. |
| virtual [ReadSByte](./readsbyte/)() | Reads a single byte from the input stream and returns it as a signed 8-bit integer value. |
| virtual [ReadSingle](./readsingle/)() | Reads 4 bytes from the input stream and returns them as a single-precision floating point value. |
| virtual [ReadString](./readstring/)() | Reads a string from the current stream. The string is prefixed with the length, encoded as an integer seven bits at a time. |
| virtual [ReadUInt16](./readuint16/)() | Reads 2 bytes from the input stream and returns them as an unsigned 16-bit integer value. |
| virtual [ReadUInt32](./readuint32/)() | Reads 4 bytes from the input stream and returns them as an unsigned 32-bit integer value. |
| virtual [ReadUInt64](./readuint64/)() | Reads 8 bytes from the input stream and returns them as an unsigned 64-bit integer value. |
| virtual [~BinaryReader](./~binaryreader/)() | Destructor. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
