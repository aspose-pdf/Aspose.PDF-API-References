---
title: System::IO::BufferedStream class
linktitle: BufferedStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BufferedStream class. Adds a buffering layer on top of another stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.io/bufferedstream/
---
## BufferedStream class


Adds a buffering layer on top of another stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BufferedStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&) | Constructs an [BufferedStream](./) object that wraps the specified stream and uses a 4096 bytes long buffer. |
| [BufferedStream](./bufferedstream/)(const SharedPtr\<Stream\>\&, int) | Constructs an [BufferedStream](./) object that wraps the specified stream and uses a buffer of the specified size. |
| [Flush](./flush/)() override | Writes the content of the buffer to the underlying stream. |
| [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| [get_Length](./get_length/)() const override | Returns the length of the stream. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the underlying stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the underlying stream and writes them to the specified byte array. |
| [ReadByte](./readbyte/)() override | Reads a single byte from the underlying stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Flushes the buffer to the underlying stream and then sets the stream's position. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the underlying stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the underlying stream. |
| [WriteByte](./writebyte/)(uint8_t) override | Writes the specified unsigned 8-bit integer value to the underlying stream. |
| virtual [~BufferedStream](./~bufferedstream/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
