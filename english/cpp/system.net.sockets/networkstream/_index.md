---
title: System::Net::Sockets::NetworkStream class
linktitle: NetworkStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::NetworkStream class. Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous read operation. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Initiates an asynchronous write operation. |
| [Close](./close/)(int) | Closes the current instance after the specified time expires. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Waits until the specified asynchronous read operation completes. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Ends an asynchronous write operation. Waits until the specified asynchronous write operation completes. |
| [Flush](./flush/)() override | Clears this stream's buffers and writes all buffered data to the underlying storage. |
| [get_CanRead](./get_canread/)() const override | RTTI information. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanTimeout](./get_cantimeout/)() const override | Gets a value that determines whether the current stream can time out. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| [get_DataAvailable](./get_dataavailable/)() const | Returns a value that indicates if the there is available data to read. |
| [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| [get_Socket](./get_socket/)() | Gets the underlying [Socket](../socket/). |
| [get_WriteTimeout](./get_writetimeout/)() const override | Gets a value, in milliseconds, that determines how long the stream will attempt to write before timing out. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Constructs a new instance. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Constructs a new instance. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Constructs a new instance. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Sets the stream's position. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Sets a value that determines whether the current stream can time out. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Sets a value, in milliseconds, that determines how long the stream will attempt to read before timing out. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| virtual [~NetworkStream](./~networkstream/)() | Destructs the current instance. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
