---
title: System::Text::Json::JsonWriterHelper class
linktitle: JsonWriterHelper
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonWriterHelper class in C++.'
type: docs
weight: 2100
url: /cpp/system.text.json/jsonwriterhelper/
---
## JsonWriterHelper class




```cpp
class JsonWriterHelper
```

## Methods

| Method | Description |
| --- | --- |
| static [EscapeString](./escapestring/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>, int32_t\&) |  |
| static [EscapeString](./escapestring/)(ReadOnlySpan\<uint8_t\>, Span\<uint8_t\>, int32_t, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>, int32_t\&, int32_t\&, bool) |  |
| static [EscapeString](./escapestring/)(ReadOnlySpan\<char16_t\>, Span\<char16_t\>, int32_t, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>, int32_t\&) |  |
| static [EscapeString](./escapestring/)(ReadOnlySpan\<char16_t\>, Span\<char16_t\>, int32_t, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>, int32_t\&, int32_t\&, bool) |  |
| static [GetMaxEscapedLength](./getmaxescapedlength/)(int32_t, int32_t) |  |
| [JsonWriterHelper](./jsonwriterhelper/)() |  |
| static [NeedsEscaping](./needsescaping/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>) |  |
| static [NeedsEscaping](./needsescaping/)(ReadOnlySpan\<char16_t\>, System::SharedPtr\<Encodings::Web::JavaScriptEncoder\>) |  |
| static [ToUtf8](./toutf8/)(ReadOnlySpan\<char16_t\>, Span\<uint8_t\>, int32_t\&) |  |
| static [TrimDateTimeOffset](./trimdatetimeoffset/)(Span\<uint8_t\>, int32_t\&) |  |
| static [ValidateDouble](./validatedouble/)(double) |  |
| static [ValidateIndentCharacter](./validateindentcharacter/)(char16_t) |  |
| static [ValidateIndentSize](./validateindentsize/)(int32_t) |  |
| static [ValidateNewLine](./validatenewline/)(String) |  |
| static [ValidateNumber](./validatenumber/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ValidateProperty](./validateproperty/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ValidateProperty](./validateproperty/)(ReadOnlySpan\<char16_t\>) |  |
| static [ValidatePropertyAndValue](./validatepropertyandvalue/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [ValidatePropertyAndValue](./validatepropertyandvalue/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<char16_t\>) |  |
| static [ValidatePropertyAndValue](./validatepropertyandvalue/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [ValidatePropertyAndValue](./validatepropertyandvalue/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<char16_t\>) |  |
| static [ValidatePropertyNameLength](./validatepropertynamelength/)(ReadOnlySpan\<char16_t\>) |  |
| static [ValidatePropertyNameLength](./validatepropertynamelength/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ValidateSingle](./validatesingle/)(float) |  |
| static [ValidateValue](./validatevalue/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ValidateValue](./validatevalue/)(ReadOnlySpan\<char16_t\>) |  |
| static [WriteDateTimeOffsetTrimmed](./writedatetimeoffsettrimmed/)(Span\<uint8_t\>, DateTimeOffset, int32_t\&) |  |
| static [WriteDateTimeTrimmed](./writedatetimetrimmed/)(Span\<uint8_t\>, DateTime, int32_t\&) |  |
| static [WriteIndentation](./writeindentation/)(Span\<uint8_t\>, int32_t, uint8_t) |  |
| static [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, JsonWriterHelper::WriteCallback\<T\>) |  |
## Fields

| Field | Description |
| --- | --- |
| static [LastAsciiCharacter](./lastasciicharacter/) |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [WriteCallback](./writecallback/) |  |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
