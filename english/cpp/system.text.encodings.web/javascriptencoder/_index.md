---
title: System::Text::Encodings::Web::JavaScriptEncoder class
linktitle: JavaScriptEncoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encodings::Web::JavaScriptEncoder class. Represents a JavaScript/JSON text encoder used to escape characters that are not safe to embed directly in a JavaScript or JSON string literal in C++.'
type: docs
weight: 100
url: /cpp/system.text.encodings.web/javascriptencoder/
---
## JavaScriptEncoder class


Represents a JavaScript/JSON text encoder used to escape characters that are not safe to embed directly in a JavaScript or JSON string literal.

```cpp
class JavaScriptEncoder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Encode](./encode/)(ReadOnlySpan\<char16_t\>, Span\<char16_t\>, int32_t\&, int32_t\&, bool) | Escapes a UTF-16 input span into a UTF-16 destination span. |
| [EncodeUtf8](./encodeutf8/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t\&, int32_t\&, bool) | Escapes a UTF-8 input span into a UTF-8 destination span. |
| [FindFirstCharacterToEncode](./findfirstcharactertoencode/)(const char16_t *, int32_t) const | Finds the index of the first UTF-16 character that needs to be escaped. |
| [FindFirstCharacterToEncodeUtf8](./findfirstcharactertoencodeutf8/)(ReadOnlySpan\<uint8_t\>) const | Finds the index of the first UTF-8 byte that needs to be escaped. |
| static [get_Default](./get_default/)() | Returns the shared instance of the default encoder. |
| explicit [JavaScriptEncoder](./javascriptencoder/)(bool) | Constructs an encoder in the default or relaxed mode. |
## Remarks


Two modes are provided:* the default encoder escapes all non-ASCII characters and HTML-sensitive characters as \uXXXX;
* the relaxed encoder escapes only the characters that are mandatory for JSON ("\\", '"' and control characters) and passes everything else through.


## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Encodings::Web](../)
* Library [Aspose.PDF for C++](../../)
