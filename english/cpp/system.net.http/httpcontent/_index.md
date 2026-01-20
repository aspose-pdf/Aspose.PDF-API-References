---
title: System::Net::Http::HttpContent class
linktitle: HttpContent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::HttpContent class. Represents content of an HTTP entity. Object of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.net.http/httpcontent/
---
## HttpContent class


Represents content of an HTTP entity. [Object](../../system/object/) of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpContent : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the current instance. This method also disposes the stream that is returned by 'ReadAsStream' and the memory buffer if it is created. |
| [get_Headers](./get_headers/)() | Returns the HTTP content headers. |
| [LoadIntoBuffer](./loadintobuffer/)() | Serializes content to a memory buffer. |
| [LoadIntoBuffer](./loadintobuffer/)(int64_t) | Serializes content to a memory buffer. |
| [ReadAsByteArray](./readasbytearray/)() | Serializes content and returns a byte array. |
| [ReadAsStream](./readasstream/)() | Serializes content and returns a stream. |
| [ReadAsString](./readasstring/)() | Serializes content and returns a string. |
| virtual [TryComputeLength](./trycomputelength/)(int64_t\&) | Tries to calculate the content size. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultStringEncoding](./defaultstringencoding/) | The default encoding. |
| static [MaxBufferSize](./maxbuffersize/) | The maximum number of bytes. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
