---
title: System::Security::Cryptography::CryptoStream class
linktitle: CryptoStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::CryptoStream class. Stream implementation that wraps existing stream with a cryptographic function. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.security.cryptography/cryptostream/
---
## CryptoStream class


Stream implementation that wraps existing stream with a cryptographic function. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes connection. |
| [CryptoStream](./cryptostream/)(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) | Constructor. |
| [Flush](./flush/)() override | Empties buffer into wrapped stream. Does nothing as transform algorithm can be still waiting for more data. |
| [FlushFinalBlock](./flushfinalblock/)() | Writes the data which is still in the buffer to stream. |
| [get_CanRead](./get_canread/)() const override | Checks if stream is readable. |
| [get_CanSeek](./get_canseek/)() const override | Checks if stream is seekable. |
| [get_CanWrite](./get_canwrite/)() const override | Checks if stream is writable. |
| [get_Length](./get_length/)() const override | Gets length of stream. Not supported. |
| [get_Position](./get_position/)() const override | Gets current position in stream. Not supported. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Reads data from stream. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads data from stream. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Seeks position in stream. Not supported. |
| [set_Position](./set_position/)(int64_t) override | Seeks position in stream. Not supported. |
| [SetLength](./setlength/)(int64_t) override | Seeks size of stream. Not supported. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Writes data to stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes data to stream. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../../system.io/stream/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
