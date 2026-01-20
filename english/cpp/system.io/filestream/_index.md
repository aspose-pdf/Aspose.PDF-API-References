---
title: System::IO::FileStream class
linktitle: FileStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileStream class. Represents a file stream supporting synchronous and asynchronous read and write operations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1500
url: /cpp/system.io/filestream/
---
## FileStream class


Represents a file stream supporting synchronous and asynchronous read and write operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the current [FileStream](./) object. |
| [FileStream](./filestream/)(const String\&, FileMode) | Constructs a new instance of [FileStream](./) class and initializes it with the specified parameters. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) | Constructs a new instance of [FileStream](./) class and initializes it with the specified parameters. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) | Constructs a new instance of [FileStream](./) class and initializes it with the specified parameters. |
| [FileStream](./filestream/)(const FileStream\&) |  |
| [Flush](./flush/)() override | Clears this stream's buffers and writes all buffered data to the underlying file. |
| [Flush](./flush/)(bool) | Clears this stream's buffers and writes all buffered data to the underlying file. Synonym for method [Flush()](./flush/). |
| [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) override | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| [get_Name](./get_name/)() const | Returns the name of the file encapsulated by the current [FileStream](./) object. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| [operator=](./operator=/)(const FileStream\&) |  |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| [ReadByte](./readbyte/)() override | Reads a single byte from the stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Flushes the stream and then sets the stream's position. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) override | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| [WriteByte](./writebyte/)(uint8_t) override | Writes the specified unsigned 8-bit integer value to the stream. |
| [~FileStream](./~filestream/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Default value of the number of bytes bufferred during read and write operations. |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
