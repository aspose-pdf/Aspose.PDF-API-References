---
title: "Clase System::Web::HttpUtility"
linktitle: "HttpUtility"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::HttpUtility. Clase de servicio que codifica y decodifica partes de URL hacia y desde fragmentos de escape hexadecimales en C++."
type: docs
weight: 300
url: /es/cpp/system.web/httputility/
---
## HttpUtility class


Clase de servicio que codifica y decodifica partes de URL hacia y desde fragmentos de escape hexadecimales.

```cpp
class HttpUtility : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [HtmlDecode](./htmldecode/)(const String\&) | Decodifica fragmento Html. |
| static [HtmlDecode](./htmldecode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Decodifica fragmento Html. |
| static [HtmlEncode](./htmlencode/)(const String\&) | Codifica fragmento Html. |
| static [HtmlEncode](./htmlencode/)(const SharedPtr\<Object\>\&) | Codifica fragmento Html. |
| static [HtmlEncode](./htmlencode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Codifica fragmento Html. |
| static [UrlDecode](./urldecode/)(String) | Decodifica fragmento URI desde cadena. |
| static [UrlDecode](./urldecode/)(String, System::SharedPtr\<Text::Encoding\>) | Decodifica fragmento URI desde cadena. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica fragmento URI desde matriz de bytes. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica fragmento URI desde matriz de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Decodifica fragmento URI desde matriz de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&) | Decodifica fragmento URI desde cadena de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica fragmento URI desde cadena. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodifica fragmento URI desde matriz de bytes. |
| static [UrlEncode](./urlencode/)(String) | Codifica fragmento URI. |
| static [UrlEncode](./urlencode/)(String, const System::SharedPtr\<Text::Encoding\>\&) | Codifica fragmento URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&) | Codifica fragmento URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Codifica fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&) | Codifica fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Codifica fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Codifica fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Codifica fragmento URI. |
| static [UrlEncodeUnicode](./urlencodeunicode/)(const String\&) | Codifica fragmento URI usando Unicode. |
| static [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const String\&) | Codifica fragmento URI usando Unicode. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.PDF for C++](../../)
