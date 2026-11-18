---
title: System::Text::Json::Utf8JsonWriter class
linktitle: Utf8JsonWriter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Utf8JsonWriter class in C++.'
type: docs
weight: 2800
url: /cpp/system.text.json/utf8jsonwriter/
---
## Utf8JsonWriter class




```cpp
class Utf8JsonWriter : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Does nothing. |
| [Flush](./flush/)() |  |
| [get_BytesCommitted](./get_bytescommitted/)() |  |
| [get_BytesPending](./get_bytespending/)() |  |
| [get_CurrentDepth](./get_currentdepth/)() |  |
| [get_Options](./get_options/)() |  |
| [Reset](./reset/)() |  |
| [Reset](./reset/)(System::SharedPtr\<IO::Stream\>) |  |
| [Reset](./reset/)(System::SharedPtr\<IO::Stream\>, JsonWriterOptions) |  |
| [Reset](./reset/)(System::SharedPtr\<Buffers::IBufferWriter\<uint8_t\>\>) |  |
| [Reset](./reset/)(System::SharedPtr\<Buffers::IBufferWriter\<uint8_t\>\>, JsonWriterOptions) |  |
| [Utf8JsonWriter](./utf8jsonwriter/)(System::SharedPtr\<Buffers::IBufferWriter\<uint8_t\>\>, JsonWriterOptions) |  |
| [Utf8JsonWriter](./utf8jsonwriter/)(System::SharedPtr\<IO::Stream\>, JsonWriterOptions) |  |
| [WriteBase64String](./writebase64string/)(JsonEncodedText, ReadOnlySpan\<uint8_t\>) |  |
| [WriteBase64String](./writebase64string/)(String, ReadOnlySpan\<uint8_t\>) |  |
| [WriteBase64String](./writebase64string/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<uint8_t\>) |  |
| [WriteBase64String](./writebase64string/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| [WriteBase64StringSegment](./writebase64stringsegment/)(ReadOnlySpan\<uint8_t\>, bool) |  |
| [WriteBase64StringValue](./writebase64stringvalue/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteBoolean](./writeboolean/)(JsonEncodedText, bool) |  |
| [WriteBoolean](./writeboolean/)(String, bool) |  |
| [WriteBoolean](./writeboolean/)(ReadOnlySpan\<char16_t\>, bool) |  |
| [WriteBoolean](./writeboolean/)(ReadOnlySpan\<uint8_t\>, bool) |  |
| [WriteBooleanValue](./writebooleanvalue/)(bool) |  |
| [WriteEndArray](./writeendarray/)() |  |
| [WriteEndObject](./writeendobject/)() |  |
| [WriteNull](./writenull/)(JsonEncodedText) |  |
| [WriteNull](./writenull/)(String) |  |
| [WriteNull](./writenull/)(ReadOnlySpan\<char16_t\>) |  |
| [WriteNull](./writenull/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteNullValue](./writenullvalue/)() |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, Decimal) |  |
| [WriteNumber](./writenumber/)(String, Decimal) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, Decimal) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, Decimal) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, double) |  |
| [WriteNumber](./writenumber/)(String, double) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, double) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, double) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, float) |  |
| [WriteNumber](./writenumber/)(String, float) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, float) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, float) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, int64_t) |  |
| [WriteNumber](./writenumber/)(String, int64_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, int64_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, int64_t) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, int32_t) |  |
| [WriteNumber](./writenumber/)(String, int32_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, int32_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, int32_t) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, uint64_t) |  |
| [WriteNumber](./writenumber/)(String, uint64_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, uint64_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, uint64_t) |  |
| [WriteNumber](./writenumber/)(JsonEncodedText, uint32_t) |  |
| [WriteNumber](./writenumber/)(String, uint32_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<char16_t\>, uint32_t) |  |
| [WriteNumber](./writenumber/)(ReadOnlySpan\<uint8_t\>, uint32_t) |  |
| [WriteNumberValue](./writenumbervalue/)(Decimal) |  |
| [WriteNumberValue](./writenumbervalue/)(double) |  |
| [WriteNumberValue](./writenumbervalue/)(float) |  |
| [WriteNumberValue](./writenumbervalue/)(int32_t) |  |
| [WriteNumberValue](./writenumbervalue/)(int64_t) |  |
| [WriteNumberValue](./writenumbervalue/)(uint32_t) |  |
| [WriteNumberValue](./writenumbervalue/)(uint64_t) |  |
| [WritePropertyName](./writepropertyname/)(JsonEncodedText) |  |
| [WritePropertyName](./writepropertyname/)(String) |  |
| [WritePropertyName](./writepropertyname/)(const char16_t *) |  |
| [WritePropertyName](./writepropertyname/)(ReadOnlySpan\<char16_t\>) |  |
| [WritePropertyName](./writepropertyname/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteRawValue](./writerawvalue/)(String, bool) |  |
| [WriteRawValue](./writerawvalue/)(ReadOnlySpan\<char16_t\>, bool) |  |
| [WriteRawValue](./writerawvalue/)(ReadOnlySpan\<uint8_t\>, bool) |  |
| [WriteRawValue](./writerawvalue/)(Buffers::ReadOnlySequence\<uint8_t\>, bool) |  |
| [WriteStartArray](./writestartarray/)() |  |
| [WriteStartArray](./writestartarray/)(JsonEncodedText) |  |
| [WriteStartArray](./writestartarray/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteStartArray](./writestartarray/)(String) |  |
| [WriteStartArray](./writestartarray/)(ReadOnlySpan\<char16_t\>) |  |
| [WriteStartObject](./writestartobject/)() |  |
| [WriteStartObject](./writestartobject/)(JsonEncodedText) |  |
| [WriteStartObject](./writestartobject/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteStartObject](./writestartobject/)(String) |  |
| [WriteStartObject](./writestartobject/)(ReadOnlySpan\<char16_t\>) |  |
| [WriteString](./writestring/)(JsonEncodedText, DateTime) |  |
| [WriteString](./writestring/)(String, DateTime) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, DateTime) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, DateTime) |  |
| [WriteString](./writestring/)(JsonEncodedText, DateTimeOffset) |  |
| [WriteString](./writestring/)(String, DateTimeOffset) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, DateTimeOffset) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, DateTimeOffset) |  |
| [WriteString](./writestring/)(JsonEncodedText, Guid) |  |
| [WriteString](./writestring/)(String, Guid) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, Guid) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, Guid) |  |
| [WriteString](./writestring/)(JsonEncodedText, JsonEncodedText) |  |
| [WriteString](./writestring/)(String, JsonEncodedText) |  |
| [WriteString](./writestring/)(String, String) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<char16_t\>) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| [WriteString](./writestring/)(JsonEncodedText, String) |  |
| [WriteString](./writestring/)(JsonEncodedText, ReadOnlySpan\<char16_t\>) |  |
| [WriteString](./writestring/)(String, ReadOnlySpan\<char16_t\>) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<char16_t\>) |  |
| [WriteString](./writestring/)(JsonEncodedText, ReadOnlySpan\<uint8_t\>) |  |
| [WriteString](./writestring/)(String, ReadOnlySpan\<uint8_t\>) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<uint8_t\>) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, JsonEncodedText) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<char16_t\>, String) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, JsonEncodedText) |  |
| [WriteString](./writestring/)(ReadOnlySpan\<uint8_t\>, String) |  |
| [WriteStringValue](./writestringvalue/)(DateTime) |  |
| [WriteStringValue](./writestringvalue/)(DateTimeOffset) |  |
| [WriteStringValue](./writestringvalue/)(Guid) |  |
| [WriteStringValue](./writestringvalue/)(JsonEncodedText) |  |
| [WriteStringValue](./writestringvalue/)(String) |  |
| [WriteStringValue](./writestringvalue/)(ReadOnlySpan\<char16_t\>) |  |
| [WriteStringValue](./writestringvalue/)(ReadOnlySpan\<uint8_t\>) |  |
| [WriteStringValueSegment](./writestringvaluesegment/)(ReadOnlySpan\<char16_t\>, bool) |  |
| [WriteStringValueSegment](./writestringvaluesegment/)(ReadOnlySpan\<uint8_t\>, bool) |  |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
