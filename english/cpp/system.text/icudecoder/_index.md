---
title: System::Text::ICUDecoder class
linktitle: ICUDecoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUDecoder class. Decoder that uses ICU for decoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.text/icudecoder/
---
## ICUDecoder class


[Decoder](../decoder/) that uses ICU for decoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUDecoder : public System::Text::Decoder
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Converts bytes to characters. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Converts bytes to characters. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Gets the number of characters needed to decode a buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Gets the number of characters needed to decode a buffer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Gets the number of characters needed to decode a buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Get the characters that result from decoding a buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Get the characters that result from decoding a buffer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Get the characters that result from decoding a buffer. |
| [ICUDecoder](./icudecoder/)(ICUEncoding *) | Constructor. |
| virtual [Reset](./reset/)() | Sets internal variables to initial state. |
| virtual [~ICUDecoder](./~icudecoder/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Base](./base/) | [Base](./base/) type. |
## See Also

* Class [Decoder](../decoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
