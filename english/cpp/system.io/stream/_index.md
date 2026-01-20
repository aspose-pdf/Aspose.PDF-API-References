---
title: System::IO::Stream class
linktitle: Stream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Stream class. A base class for a variety of stream implementations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.io/stream/
---
## Stream class


A base class for a variety of stream implementations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Stream : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Initiates an asynchronous read operation. |
| virtual [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Initiates an asynchronous write operation. |
| virtual [Close](./close/)() | Closes the stream. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&) | Copies bytes to the specified stream. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&, int32_t) | Copies bytes to the specified stream, using the specified buffer size. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the stream. |
| virtual [EndRead](./endread/)(System::SharedPtr\<System::IAsyncResult\>) | Waits until the specified asynchronous read operation completes. |
| virtual [EndWrite](./endwrite/)(System::SharedPtr\<System::IAsyncResult\>) | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| virtual [Flush](./flush/)() | Clears this stream's buffers and writes all buffered data to the underlying storage. |
| virtual [FlushAsync](./flushasync/)(const Threading::CancellationToken\&) | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| [FlushAsync](./flushasync/)() | Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests. |
| virtual [get_CanRead](./get_canread/)() const | Determines if the stream is readable. |
| virtual [get_CanSeek](./get_canseek/)() const | Determines if the stream supports seeking. |
| virtual [get_CanTimeout](./get_cantimeout/)() const | Gets a value that determines whether the current stream can time out. |
| virtual [get_CanWrite](./get_canwrite/)() const | Determines if the stream is writable. |
| virtual [get_Length](./get_length/)() const | Returns the length of the stream in bytes. |
| virtual [get_Position](./get_position/)() const | Returns the current position of the stream. |
| virtual [get_ReadTimeout](./get_readtimeout/)() const | Gets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual [get_WriteTimeout](./get_writetimeout/)() const | Gets a value, in milliseconds, that determines how long the stream will attempt to write before timing out. |
| virtual [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| virtual [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| virtual [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| [ReadAsync](./readasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| virtual [ReadByte](./readbyte/)() | Reads a single byte from the stream and returns a 32-bit integer value equivalent to the value of the read byte. |
| virtual [Seek](./seek/)(int64_t, SeekOrigin) | Sets the position of the stream represented by the current object. |
| virtual [set_Position](./set_position/)(int64_t) | Sets the stream's position. |
| virtual [set_ReadTimeout](./set_readtimeout/)(int) | Sets a value that determines whether the current stream can time out. |
| virtual [set_WriteTimeout](./set_writetimeout/)(int) | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| virtual [SetLength](./setlength/)(int64_t) | Sets the length of the stream represented by the current object. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Writes the specified subrange of bytes from the specified byte array to the stream. |
| virtual [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [Write](./write/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Writes the specified subrange of bytes from the specified byte array to the stream. |
| virtual [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| [WriteAsync](./writeasync/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |
| virtual [WriteByte](./writebyte/)(uint8_t) | Writes the specified unsigned 8-bit integer value to the stream. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](./null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for a shared pointer to this class. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
