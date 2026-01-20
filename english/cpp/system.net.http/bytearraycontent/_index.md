---
title: System::Net::Http::ByteArrayContent class
linktitle: ByteArrayContent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::ByteArrayContent class. Represents HTTP content as a byte array. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net.http/bytearraycontent/
---
## ByteArrayContent class


Represents HTTP content as a byte array. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ByteArrayContent : public System::Net::Http::HttpContent
```

## Methods

| Method | Description |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>) | RTTI information. |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Constructs a new instance. |
| [TryComputeLength](./trycomputelength/)(int64_t\&) override | Tries to calculate the byte array length. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | The default encoding. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | The maximum number of bytes. |
## See Also

* Class [HttpContent](../httpcontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
