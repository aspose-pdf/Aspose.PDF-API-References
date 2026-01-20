---
title: System::Text::ICUEncoding class
linktitle: ICUEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUEncoding class. ICU-based encoding implementation. FOR INTERNAL USE. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2200
url: /cpp/system.text/icuencoding/
---
## ICUEncoding class


ICU-based encoding implementation. FOR INTERNAL USE. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## Methods

| Method | Description |
| --- | --- |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | RTTI. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const String\&) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Get the bytes that result from encoding a character buffer. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Get the number of characters needed to decode a byte buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Get the number of characters needed to decode a byte buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Get the number of characters needed to decode a byte buffer. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Get the characters that result from decoding a byte buffer. |
| [GetDecoder](./getdecoder/)() override | Get a decoder that forwards requests to this object. |
| [GetEncoder](./getencoder/)() override | Get an encoder that forwards requests to this object. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Get the maximum number of bytes needed to encode a specified number of characters. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Get the maximum number of characters needed to decode a specified number of bytes. |
| [GetPreamble](./getpreamble/)() override | Returns a sequence of bytes that denotes the encoding (e. g. BOM). |
| [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| [operator==](./operator==/)(const ICUEncoding\&) const | Compares encodings using codepages. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
## See Also

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
