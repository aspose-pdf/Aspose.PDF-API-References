---
title: Aspose::Pdf::OptimizedMemoryStream class
linktitle: OptimizedMemoryStream
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream class. Defines a MemoryStream that can contains more standard capacity in C++.'
type: docs
weight: 12400
url: /cpp/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class


Defines a MemoryStream that can contains more standard capacity.

```cpp
class OptimizedMemoryStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [Flush](./flush/)() override | The function overrided. |
| [get_BufferSize](./get_buffersize/)() const | Gets the size of the underlying buffers. |
| [get_CanRead](./get_canread/)() const override | When overridden in a derived class, gets a value indicating whether the current stream supports reading. |
| [get_CanSeek](./get_canseek/)() const override | When overridden in a derived class, gets a value indicating whether the current stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | When overridden in a derived class, gets a value indicating whether the current stream supports writing. |
| [get_FreeOnDispose](./get_freeondispose/)() const | Gets a value indicating whether to free the underlying buffers on dispose. |
| [get_Length](./get_length/)() const override | When overridden in a derived class, gets the length in bytes of the stream. |
| [get_Position](./get_position/)() const override | When overridden in a derived class, gets or sets the position within the current stream. |
| [OptimizedMemoryStream](./optimizedmemorystream/)() | Initializes a new instance of the [OptimizedMemoryStream](./) class. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t, System::ArrayPtr\<uint8_t\>) | Initializes a new instance of the [OptimizedMemoryStream](./) class based on the specified byte array. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(int32_t) | Initializes a new instance of the [OptimizedMemoryStream](./) class. |
| [OptimizedMemoryStream](./optimizedmemorystream/)(System::ArrayPtr\<uint8_t\>) | Initializes a new instance of the [OptimizedMemoryStream](./) class based on the specified byte array. |
| [Read](./read/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [ReadByte](./readbyte/)() override | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [Seek](./seek/)(int64_t, System::IO::SeekOrigin) override | When overridden in a derived class, sets the position within the current stream. |
| [set_BufferSize](./set_buffersize/)(int32_t) | Sets the size of the underlying buffers. |
| [set_FreeOnDispose](./set_freeondispose/)(bool) | Sets a value indicating whether to free the underlying buffers on dispose. |
| [set_Position](./set_position/)(int64_t) override | When overridden in a derived class, gets or sets the position within the current stream. |
| [SetLength](./setlength/)(int64_t) override | When overridden in a derived class, sets the length of the current stream. |
| [ToArray](./toarray/)() | Converts the current stream to a byte array. |
| [Write](./write/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [WriteByte](./writebyte/)(uint8_t) override | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [WriteTo](./writeto/)(System::SharedPtr\<System::IO::Stream\>) | Writes to the specified stream. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Default buffer size value in bytes. |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../../system.io/stream/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
