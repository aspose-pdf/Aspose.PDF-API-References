---
title: System::Text::UTF7Encoding class
linktitle: UTF7Encoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UTF7Encoding class. UTF-7 encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.text/utf7encoding/
---
## UTF7Encoding class


UTF-7 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones encoding object. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares with object. |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | Get the number of characters needed to encode a string. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | Get the number of characters needed to encode a character buffer. |
| [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) override | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const String\&) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Get the bytes that result from encoding a character buffer. |
| [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) override | Get the number of characters needed to decode a byte buffer. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Get the number of characters needed to decode a byte buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Get the number of characters needed to decode a byte buffer. |
| [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) override | Get the characters that result from decoding a byte buffer. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Get the characters that result from decoding a byte buffer. |
| [GetDecoder](./getdecoder/)() override | Get a decoder that forwards requests to this object. |
| [GetEncoder](./getencoder/)() override | Get an encoder that forwards requests to this object. |
| [GetHashCode](./gethashcode/)() const override | Gets encoding hash code. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Get the maximum number of bytes needed to encode a specified number of characters. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Get the maximum number of characters needed to decode a specified number of bytes. |
| [GetString](./getstring/)(ArrayPtr\<uint8_t\>, int, int) override | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(uint8_t *, int) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&) | Decodes a buffer of bytes into a string. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>\&) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&, int, int) | Decodes a buffer of bytes into a string. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>, int, int) | Decodes a buffer of bytes into a string. |
| [operator==](./operator==/)(const UTF7Encoding\&) const | Compares encodings parameters. |
| [UTF7Encoding](./utf7encoding/)() | Constructor. |
| [UTF7Encoding](./utf7encoding/)(bool) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Magic number used by [Windows](../../system.windows/) for UTF-7 codepage id. |
## See Also

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
