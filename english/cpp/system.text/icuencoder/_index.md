---
title: System::Text::ICUEncoder class
linktitle: ICUEncoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUEncoder class. Encoder that uses ICU for encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.text/icuencoder/
---
## ICUEncoder class


[Encoder](../encoder/) that uses ICU for encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUEncoder : public System::Text::Encoder
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Converts characters to bytes. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Converts characters to bytes. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Gets the number of bytes needed to encode a buffer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Gets the number of bytes needed to encode a buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Get the bytes that result from encoding a buffer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Get the bytes that result from encoding a buffer. |
| [ICUEncoder](./icuencoder/)(ICUEncoding *) | Constructor. |
| virtual [Reset](./reset/)() | Sets internal variables to initial state. |
| [~ICUEncoder](./~icuencoder/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Base](./base/) | [Base](./base/) type. |
## See Also

* Class [Encoder](../encoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
