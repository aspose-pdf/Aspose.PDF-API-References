---
title: "System::Web::HttpUtility klass"
linktitle: "HttpUtility"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::HttpUtility klass. Serviceklass som kodar och avkodar URL‑delar till och från hex‑escape‑fragment i C++."
type: docs
weight: 300
url: /sv/cpp/system.web/httputility/
---
## HttpUtility class


Serviceklass som kodar och avkodar URL-delar till och från hex-escape-fragment.

```cpp
class HttpUtility : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [HtmlDecode](./htmldecode/)(const String\&) | Avkodar HTML‑fragment. |
| static [HtmlDecode](./htmldecode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Avkodar HTML‑fragment. |
| static [HtmlEncode](./htmlencode/)(const String\&) | Kodar HTML-fragment. |
| static [HtmlEncode](./htmlencode/)(const SharedPtr\<Object\>\&) | Kodar HTML-fragment. |
| static [HtmlEncode](./htmlencode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Kodar HTML-fragment. |
| static [UrlDecode](./urldecode/)(String) | Avkodar URI-fragment från sträng. |
| static [UrlDecode](./urldecode/)(String, System::SharedPtr\<Text::Encoding\>) | Avkodar URI-fragment från sträng. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) | Avkodar URI-fragment från byte-array. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) | Avkodar URI-fragment från byte-array. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Avkodar URI-fragment från byte-array. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&) | Avkodar URI-fragment från byte-sträng. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Avkodar URI-fragment från sträng. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Avkodar URI-fragment från byte-array. |
| static [UrlEncode](./urlencode/)(String) | Kodar URI-fragment. |
| static [UrlEncode](./urlencode/)(String, const System::SharedPtr\<Text::Encoding\>\&) | Kodar URI-fragment. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&) | Kodar URI-fragment. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Kodar URI-fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&) | Kodar URI-fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Kodar URI-fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Kodar URI-fragment. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Kodar URI-fragment. |
| static [UrlEncodeUnicode](./urlencodeunicode/)(const String\&) | Kodar URI-fragment med Unicode. |
| static [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const String\&) | Kodar URI-fragment med Unicode. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.PDF for C++](../../)
