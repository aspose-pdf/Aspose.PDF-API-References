---
title: System::Text::Json::Nodes::JsonNode class
linktitle: JsonNode
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Nodes::JsonNode class in C++.'
type: docs
weight: 200
url: /cpp/system.text.json.nodes/jsonnode/
---
## JsonNode class




```cpp
class JsonNode : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AsArray](./asarray/)() |  |
| [AsObject](./asobject/)() |  |
| [AsValue](./asvalue/)() |  |
| [DeepClone](./deepclone/)() |  |
| static [DeepEquals](./deepequals/)(System::SharedPtr\<JsonNode\>, System::SharedPtr\<JsonNode\>) |  |
| [get_Options](./get_options/)() |  |
| [get_Parent](./get_parent/)() |  |
| [get_Root](./get_root/)() |  |
| [GetElementIndex](./getelementindex/)() |  |
| [GetPath](./getpath/)() |  |
| [GetPropertyName](./getpropertyname/)() |  |
| [GetValue](./getvalue/)() |  |
| [GetValueKind](./getvaluekind/)() |  |
| [idx_get](./idx_get/)(int32_t) |  |
| [idx_get](./idx_get/)(String) |  |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<JsonNode\>) |  |
| [idx_set](./idx_set/)(String, System::SharedPtr\<JsonNode\>) |  |
| static [Parse](./parse/)(Utf8JsonReader\&, Nullable\<JsonNodeOptions\>) |  |
| static [Parse](./parse/)(String, Nullable\<JsonNodeOptions\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(ReadOnlySpan\<uint8_t\>, Nullable\<JsonNodeOptions\>, JsonDocumentOptions) |  |
| static [Parse](./parse/)(System::SharedPtr\<IO::Stream\>, Nullable\<JsonNodeOptions\>, JsonDocumentOptions) |  |
| static [to_Boolean](./to_boolean/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_BooleanNullable](./to_booleannullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Byte](./to_byte/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_ByteNullable](./to_bytenullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Char](./to_char/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_CharNullable](./to_charnullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DateTime](./to_datetime/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DateTimeNullable](./to_datetimenullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DateTimeOffset](./to_datetimeoffset/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DateTimeOffsetNullable](./to_datetimeoffsetnullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Decimal](./to_decimal/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DecimalNullable](./to_decimalnullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Double](./to_double/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_DoubleNullable](./to_doublenullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Guid](./to_guid/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_GuidNullable](./to_guidnullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int16](./to_int16/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int16Nullable](./to_int16nullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int32](./to_int32/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int32Nullable](./to_int32nullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int64](./to_int64/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Int64Nullable](./to_int64nullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_JsonNode](./to_jsonnode/)(bool) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<bool\>) |  |
| static [to_JsonNode](./to_jsonnode/)(uint8_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<uint8_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(char16_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<char16_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(DateTime) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<DateTime\>) |  |
| static [to_JsonNode](./to_jsonnode/)(DateTimeOffset) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<DateTimeOffset\>) |  |
| static [to_JsonNode](./to_jsonnode/)(Decimal) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<Decimal\>) |  |
| static [to_JsonNode](./to_jsonnode/)(double) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<double\>) |  |
| static [to_JsonNode](./to_jsonnode/)(Guid) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<Guid\>) |  |
| static [to_JsonNode](./to_jsonnode/)(int16_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<int16_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(int32_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<int32_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(int64_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<int64_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(int8_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<int8_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(float) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<float\>) |  |
| static [to_JsonNode](./to_jsonnode/)(String) |  |
| static [to_JsonNode](./to_jsonnode/)(uint16_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<uint16_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(uint32_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<uint32_t\>) |  |
| static [to_JsonNode](./to_jsonnode/)(uint64_t) |  |
| static [to_JsonNode](./to_jsonnode/)(Nullable\<uint64_t\>) |  |
| static [to_SByte](./to_sbyte/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_SByteNullable](./to_sbytenullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_Single](./to_single/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_SingleNullable](./to_singlenullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_String](./to_string/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt16](./to_uint16/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt16Nullable](./to_uint16nullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt32](./to_uint32/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt32Nullable](./to_uint32nullable/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt64](./to_uint64/)(System::SharedPtr\<JsonNode\>) |  |
| static [to_UInt64Nullable](./to_uint64nullable/)(System::SharedPtr\<JsonNode\>) |  |
| [ToJsonString](./tojsonstring/)(System::SharedPtr\<JsonSerializerOptions\>) |  |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| virtual [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<JsonSerializerOptions\>) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Json::Nodes](../)
* Library [Aspose.PDF for C++](../../)
