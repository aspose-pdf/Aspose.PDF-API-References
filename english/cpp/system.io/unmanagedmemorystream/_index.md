---
title: System::IO::UnmanagedMemoryStream class
linktitle: UnmanagedMemoryStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::UnmanagedMemoryStream class. Provides access to unmanaged memory. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2800
url: /cpp/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream class


Provides access to unmanaged memory. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [Flush](./flush/)() override | Does nothing. |
| [get_CanRead](./get_canread/)() const override | Determines if the stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream is writable. |
| virtual [get_Capacity](./get_capacity/)() const | Returns the current capacity of the underlying memory buffer. |
| [get_Length](./get_length/)() const override | Returns the length of the stream in bytes. |
| [get_Position](./get_position/)() const override | Returns the current position of the stream. |
| [get_PositionPointer](./get_positionpointer/)() | NOT IMPLEMENTED. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Sets the stream's position. |
| [set_PositionPointer](./set_positionpointer/)(uint8_t *) | NOT IMPLEMENTED. |
| [SetLength](./setlength/)(int64_t) override | NOT IMPLEMENTED. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t) | Constructs a new instance of [UnmanagedMemoryStream](./). |
| [UnmanagedMemoryStream](./unmanagedmemorystream/)(uint8_t *, int64_t, int64_t, FileAccess) | Constructs a new instance of [UnmanagedMemoryStream](./). |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | NOT IMPLEMENTED. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | NOT IMPLEMENTED. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
