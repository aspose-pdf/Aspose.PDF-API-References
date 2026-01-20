---
title: System::Text::Decoder class
linktitle: Decoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Decoder class. Encapsulates decoding byte sequence into character sequence. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.text/decoder/
---
## Decoder class


Encapsulates decoding byte sequence into character sequence. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Decoder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Converts bytes to characters. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Converts bytes to characters. |
| [get_Fallback](./get_fallback/)() const | Gets error handling fallback. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Gets fallback buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Gets the number of characters needed to decode a buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Gets the number of characters needed to decode a buffer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Gets the number of characters needed to decode a buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Get the characters that result from decoding a buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Get the characters that result from decoding a buffer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Get the characters that result from decoding a buffer. |
| virtual [Reset](./reset/)() | Cleans decoder internal state. |
| [set_Fallback](./set_fallback/)(const DecoderFallbackPtr\&) | Sets error handling fallback. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
