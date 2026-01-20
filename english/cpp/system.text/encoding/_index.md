---
title: System::Text::Encoding class
linktitle: Encoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoding class. Encoding services in C++.'
type: docs
weight: 1600
url: /cpp/system.text/encoding/
---
## Encoding class


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Clone](./clone/)() | Clones encoding object. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) | Converts bytes between two encodings. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) | Converts bytes between two encodings. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares encodings. |
| static [get_ASCII](./get_ascii/)() | Gets ASCII encoding. |
| static [get_BigEndianUnicode](./get_bigendianunicode/)() | Gets the standard big-endian Unicode encoding object. |
| static [get_BigEndianUTF32](./get_bigendianutf32/)() | Gets the standard big-endian UTF-32 encoding object. |
| virtual [get_BodyName](./get_bodyname/)() | Gets mail agent body compatible encoding name. |
| virtual [get_CodePage](./get_codepage/)() | Gets [Windows](../../system.windows/) codepage ID. |
| [get_DecoderFallback](./get_decoderfallback/)() const | Gets decoder fallback. |
| static [get_Default](./get_default/)() | Gets default encoding. |
| [get_EncoderFallback](./get_encoderfallback/)() const | Gets encoder fallback. |
| virtual [get_EncodingName](./get_encodingname/)() | Gets human-readable encoding name. |
| virtual [get_HeaderName](./get_headername/)() | Gets mail agent header compatible encoding name. |
| virtual [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Checks whether encoding can be used in browser to display content. |
| virtual [get_IsBrowserSave](./get_isbrowsersave/)() | Checks whether encoding can be used in browser to save content. |
| virtual [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Checks whether encoding can be used in mail client to display content. |
| virtual [get_IsMailNewsSave](./get_ismailnewssave/)() | Checks whether encoding can be used in mail client to save content. |
| [get_IsReadOnly](./get_isreadonly/)() | Checks whether encoding is read-only. |
| virtual [get_IsSingleByte](./get_issinglebyte/)() | Checks whether encoding is single byte. |
| static [get_Latin1](./get_latin1/)() | Gets Latin1 encoding. FOR INTERNAL USE. |
| static [get_Unicode](./get_unicode/)() | Gets the standard Unicode encoding object. |
| static [get_UTF32](./get_utf32/)() |  |
| static [get_UTF7](./get_utf7/)() | Gets the standard UTF-7 encoding object. |
| static [get_UTF8](./get_utf8/)() | Gets the standard UTF-8 encoding object. |
| static [get_UTF8Unmarked](./get_utf8unmarked/)() | Only internal, to be used by the class libraries: Unmarked and non-input-validating. |
| virtual [get_WebName](./get_webname/)() | Gets IANA-compatible encoding name. |
| virtual [get_WindowsCodePage](./get_windowscodepage/)() | Gets [Windows](../../system.windows/) codepage ID. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | Get the number of characters needed to encode a string. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | Get the number of characters needed to encode a character buffer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int) | Get the number of characters needed to encode a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const String\&) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Get the bytes that result from encoding a character buffer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) | Get the bytes that result from encoding a character buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Get the number of characters needed to decode a byte buffer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Get the number of characters needed to decode a byte buffer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int) | Get the number of characters needed to decode a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Get the characters that result from decoding a byte buffer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) | Get the characters that result from decoding a byte buffer. |
| virtual [GetDecoder](./getdecoder/)() | Get a decoder that forwards requests to this object. |
| virtual [GetEncoder](./getencoder/)() | Get an encoder that forwards requests to this object. |
| static [GetEncoding](./getencoding/)(const String\&) | Gets encoding by name. |
| static [GetEncoding](./getencoding/)(int) | Gets encoding by codepage. |
| static [GetEncoding](./getencoding/)(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Gets encoding by codepage. |
| static [GetEncoding](./getencoding/)(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Gets encoding by name. |
| static [GetEncodings](./getencodings/)() | Gets list of known encodings. |
| [GetHashCode](./gethashcode/)() const override | Hashes encoding. |
| virtual [GetMaxByteCount](./getmaxbytecount/)(int) | Get the maximum number of bytes needed to encode a specified number of characters. |
| virtual [GetMaxCharCount](./getmaxcharcount/)(int) | Get the maximum number of characters needed to decode a specified number of bytes. |
| virtual [GetPreamble](./getpreamble/)() | Returns a sequence of bytes that denotes the encoding (e. g. BOM). |
| virtual [GetString](./getstring/)(uint8_t *, int) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&) | Decodes a buffer of bytes into a string. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>\&) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>, int, int) | Decodes a buffer of bytes into a string. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&, int, int) | Decodes a buffer of bytes into a string. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>, int, int) | Decodes a buffer of bytes into a string. |
| [set_DecoderFallback](./set_decoderfallback/)(const DecoderFallbackPtr\&) | Sets decoder fallback. |
| [set_EncoderFallback](./set_encoderfallback/)(const EncoderFallbackPtr\&) | Sets encoder fallback. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Default codepage value. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
