---
title: System::Web::HttpUtility class
linktitle: HttpUtility
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::HttpUtility class. Service class that encodes and decodes URL parts to and from hex escape fragments in C++.'
type: docs
weight: 300
url: /cpp/system.web/httputility/
---
## HttpUtility class


Service class that encodes and decodes URL parts to and from hex escape fragments.

```cpp
class HttpUtility : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [HtmlDecode](./htmldecode/)(const String\&) | Decodes Html fragment. |
| static [HtmlDecode](./htmldecode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Decodes Html fragment. |
| static [HtmlEncode](./htmlencode/)(const String\&) | Encodes Html fragment. |
| static [HtmlEncode](./htmlencode/)(const SharedPtr\<Object\>\&) | Encodes Html fragment. |
| static [HtmlEncode](./htmlencode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Encodes Html fragment. |
| static [UrlDecode](./urldecode/)(String) | Decodes URI fragment from string. |
| static [UrlDecode](./urldecode/)(String, System::SharedPtr\<Text::Encoding\>) | Decodes URI fragment from string. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodes URI fragment from bytes array. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) | Decodes URI fragment from bytes array. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Decodes URI fragment from bytes array. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&) | Decodes URI fragment from bytes string. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodes URI fragment from string. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodes URI fragment from bytes array. |
| static [UrlEncode](./urlencode/)(String) | Encodes URI fragment. |
| static [UrlEncode](./urlencode/)(String, const System::SharedPtr\<Text::Encoding\>\&) | Encodes URI fragment. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&) | Encodes URI fragment. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Encodes URI fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&) | Encodes URI fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Encodes URI fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Encodes URI fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Encodes URI fragment. |
| static [UrlEncodeUnicode](./urlencodeunicode/)(const String\&) | Encodes URI fragment usign Unicode. |
| static [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const String\&) | Encodes URI fragment usign Unicode. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.PDF for C++](../../)
