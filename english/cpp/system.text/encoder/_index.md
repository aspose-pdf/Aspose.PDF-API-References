---
title: System::Text::Encoder class
linktitle: Encoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoder class. Encapsulates encoding character sequence into byte sequence. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.text/encoder/
---
## Encoder class


Encapsulates encoding character sequence into byte sequence. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Encoder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Converts characters to bytes. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Converts characters to bytes. |
| [get_Fallback](./get_fallback/)() const | Gets error handling fallback. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Gets fallback buffer. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Gets the number of bytes needed to encode a buffer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Gets the number of bytes needed to encode a buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Get the bytes that result from encoding a buffer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Get the bytes that result from encoding a buffer. |
| virtual [Reset](./reset/)() | Cleans encoder internal state. |
| [set_Fallback](./set_fallback/)(const EncoderFallbackPtr\&) | Sets error handling fallback. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
