---
title: System::IO::MemoryStream class
linktitle: MemoryStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::MemoryStream class. Represents a stream that reads from and writes to memory. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1800
url: /cpp/system.io/memorystream/
---
## MemoryStream class


Represents a stream that reads from and writes to memory. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MemoryStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the stream. |
| [Flush](./flush/)() override | Does nothing. |
| [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| [get_Capacity](./get_capacity/)() | Returns the current capacity of the underlying memory buffer. |
| [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| virtual [GetBuffer](./getbuffer/)() | Returns a pointer to the underlying buffer. |
| [MemoryStream](./memorystream/)() | Constructs a new instance of the [MemoryStream](./) class with initial capacity equal to 0. |
| [MemoryStream](./memorystream/)(int) | Constructs a new instance of the [MemoryStream](./) class that represents a stream based on a memory buffer of the specified size. |
| [MemoryStream](./memorystream/)(const ArrayPtr\<uint8_t\>\&, bool) | Constructs a new instance of the [MemoryStream](./) class that represents a memory stream which is connected to the specified memory buffer. A parameter specifies if the stream is writable. |
| [MemoryStream](./memorystream/)(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) | Constructs a new instance of the [MemoryStream](./) class that represents a memory stream which is connected to a segment of the specified memory buffer starting at the specified index and including the specified number of elements. Parameters specifies if the stream is writable and if method GetBytes() can be called. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [ReadByte](./readbyte/)() override | Reads a single byte from the stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Capacity](./set_capacity/)(int) | Sets the capacity of the underlying memory buffer. |
| [set_Position](./set_position/)(int64_t) override | Sets the stream's position. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. |
| virtual [ToArray](./toarray/)() | Returns a copy of underlying memory buffer as an array of bytes. |
| [TryGetBuffer](./trygetbuffer/)(ArraySegment\<uint8_t\>\&) | Returns the array of unsigned bytes from which this stream was created. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [WriteByte](./writebyte/)(uint8_t) override | Writes the specified unsigned 8-bit integer value to the stream. |
| virtual [WriteTo](./writeto/)(SharedPtr\<Stream\>) | Writes the content of the underlying buffer to the specified stream. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for a shared pointer to the self. |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
