---
title: "System::Web::HttpUtility класс"
linktitle: "HttpUtility"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::HttpUtility класс. Сервисный класс, который кодирует и декодирует части URL в hex‑экранированные фрагменты и из них в C++."
type: docs
weight: 300
url: /ru/cpp/system.web/httputility/
---
## HttpUtility class


Класс службы, который кодирует и декодирует части URL в и из hex escape fragments.

```cpp
class HttpUtility : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [HtmlDecode](./htmldecode/)(const String\&) | Декодирует HTML‑фрагмент. |
| static [HtmlDecode](./htmldecode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Декодирует HTML‑фрагмент. |
| static [HtmlEncode](./htmlencode/)(const String\&) | Кодирует HTML‑фрагмент. |
| static [HtmlEncode](./htmlencode/)(const SharedPtr\<Object\>\&) | Кодирует HTML‑фрагмент. |
| static [HtmlEncode](./htmlencode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Кодирует HTML‑фрагмент. |
| static [UrlDecode](./urldecode/)(String) | Декодирует фрагмент URI из строки. |
| static [UrlDecode](./urldecode/)(String, System::SharedPtr\<Text::Encoding\>) | Декодирует фрагмент URI из строки. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) | Декодирует фрагмент URI из массива байтов. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) | Декодирует фрагмент URI из массива байтов. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Декодирует фрагмент URI из массива байтов. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&) | Декодирует фрагмент URI из байтовой строки. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Декодирует фрагмент URI из строки. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Декодирует фрагмент URI из массива байтов. |
| static [UrlEncode](./urlencode/)(String) | Кодирует фрагмент URI. |
| static [UrlEncode](./urlencode/)(String, const System::SharedPtr\<Text::Encoding\>\&) | Кодирует фрагмент URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&) | Кодирует фрагмент URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Кодирует фрагмент URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&) | Кодирует фрагмент URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Кодирует фрагмент URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Кодирует фрагмент URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Кодирует фрагмент URI. |
| static [UrlEncodeUnicode](./urlencodeunicode/)(const String\&) | Кодирует фрагмент URI, используя Unicode. |
| static [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const String\&) | Кодирует фрагмент URI, используя Unicode. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.PDF for C++](../../)
