---
title: System::Net::Http::StringContent class
linktitle: StringContent
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::StringContent class. Represents HTTP content as a string. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.net.http/stringcontent/
---
## StringContent class


Represents HTTP content as a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringContent : public System::Net::Http::ByteArrayContent
```

## Methods

| Method | Description |
| --- | --- |
| [StringContent](./stringcontent/)(String) | RTTI information. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>) | Constructs a new instance. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>, String) | Constructs a new instance. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | The default encoding. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | The maximum number of bytes. |
## See Also

* Class [ByteArrayContent](../bytearraycontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
