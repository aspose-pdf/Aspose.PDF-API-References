---
title: System::Text::Json::JsonElement class
linktitle: JsonElement
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonElement class in C++.'
type: docs
weight: 800
url: /cpp/system.text.json/jsonelement/
---
## JsonElement class




```cpp
class JsonElement : public System::Object,
                    public System::Details::BoxableObjectBase
```

## Nested classes

* Class [ArrayEnumerator](./arrayenumerator/)
* Class [ObjectEnumerator](./objectenumerator/)
## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() |  |
| static [DeepEquals](./deepequals/)(JsonElement, JsonElement) |  |
| [EnumerateArray](./enumeratearray/)() |  |
| [EnumerateObject](./enumerateobject/)() |  |
| [Equals](./equals/)(const JsonElement\&) const |  |
| [get_ValueKind](./get_valuekind/)() |  |
| [GetArrayLength](./getarraylength/)() |  |
| [GetBoolean](./getboolean/)() |  |
| [GetByte](./getbyte/)() |  |
| [GetBytesFromBase64](./getbytesfrombase64/)() |  |
| [GetDateTime](./getdatetime/)() |  |
| [GetDateTimeOffset](./getdatetimeoffset/)() |  |
| [GetDecimal](./getdecimal/)() |  |
| [GetDouble](./getdouble/)() |  |
| [GetGuid](./getguid/)() |  |
| [GetInt16](./getint16/)() |  |
| [GetInt32](./getint32/)() |  |
| [GetInt64](./getint64/)() |  |
| [GetProperty](./getproperty/)(String) |  |
| [GetProperty](./getproperty/)(ReadOnlySpan\<char16_t\>) |  |
| [GetProperty](./getproperty/)(ReadOnlySpan\<uint8_t\>) |  |
| [GetPropertyCount](./getpropertycount/)() |  |
| [GetRawText](./getrawtext/)() |  |
| [GetSByte](./getsbyte/)() |  |
| [GetSingle](./getsingle/)() |  |
| [GetString](./getstring/)() |  |
| [GetUInt16](./getuint16/)() |  |
| [GetUInt32](./getuint32/)() |  |
| [GetUInt64](./getuint64/)() |  |
| [idx_get](./idx_get/)(int32_t) |  |
| [JsonElement](./jsonelement/)() |  |
| [operator!=](./operator!=/)(const JsonElement\&) const |  |
| [operator==](./operator==/)(const JsonElement\&) const |  |
| static [Parse](./parse/)(ReadOnlySpan\<uint8_t\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(ReadOnlySpan\<char16_t\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(String, JsonDocumentOptions) |  |
| static [ParseValue](./parsevalue/)(Utf8JsonReader\&) |  |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [TryGetByte](./trygetbyte/)(uint8_t\&) |  |
| [TryGetBytesFromBase64](./trygetbytesfrombase64/)(System::SharedPtr\<Array\<uint8_t\>\>\&) |  |
| [TryGetDateTime](./trygetdatetime/)(DateTime\&) |  |
| [TryGetDateTimeOffset](./trygetdatetimeoffset/)(DateTimeOffset\&) |  |
| [TryGetDecimal](./trygetdecimal/)(Decimal\&) |  |
| [TryGetDouble](./trygetdouble/)(double\&) |  |
| [TryGetGuid](./trygetguid/)(Guid\&) |  |
| [TryGetInt16](./trygetint16/)(int16_t\&) |  |
| [TryGetInt32](./trygetint32/)(int32_t\&) |  |
| [TryGetInt64](./trygetint64/)(int64_t\&) |  |
| [TryGetProperty](./trygetproperty/)(String, JsonElement\&) |  |
| [TryGetProperty](./trygetproperty/)(ReadOnlySpan\<char16_t\>, JsonElement\&) |  |
| [TryGetProperty](./trygetproperty/)(ReadOnlySpan\<uint8_t\>, JsonElement\&) |  |
| [TryGetSByte](./trygetsbyte/)(int8_t\&) |  |
| [TryGetSingle](./trygetsingle/)(float\&) |  |
| [TryGetUInt16](./trygetuint16/)(uint16_t\&) |  |
| [TryGetUInt32](./trygetuint32/)(uint32_t\&) |  |
| [TryGetUInt64](./trygetuint64/)(uint64_t\&) |  |
| static [TryParseValue](./tryparsevalue/)(Utf8JsonReader\&, Nullable\<JsonElement\>\&) |  |
| [ValueEquals](./valueequals/)(String) |  |
| [ValueEquals](./valueequals/)(ReadOnlySpan\<uint8_t\>) |  |
| [ValueEquals](./valueequals/)(ReadOnlySpan\<char16_t\>) |  |
| [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
