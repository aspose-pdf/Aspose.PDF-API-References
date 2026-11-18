---
title: System::Text::Json::JsonSerializer class
linktitle: JsonSerializer
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::JsonSerializer class in C++.'
type: docs
weight: 1900
url: /cpp/system.text.json/jsonserializer/
---
## JsonSerializer class




```cpp
class JsonSerializer
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateExtensionDataProperty](./createextensiondataproperty/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<JsonDocument\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<JsonDocument\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<JsonDocument\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(JsonElement, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(JsonElement, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(JsonElement, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<Nodes::JsonNode\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<Nodes::JsonNode\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<Nodes::JsonNode\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(Utf8JsonReader\&, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(Utf8JsonReader\&, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(Utf8JsonReader\&, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(String, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<char16_t\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(String, System::SharedPtr\<JsonSerializerOptions\>) |  |
| static [Deserialize](./deserialize/)(String, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<char16_t\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(String, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<char16_t\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Deserialize](./deserialize/)(ReadOnlySpan\<uint8_t\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [GetMetadataPropertyName](./getmetadatapropertyname/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Serialization::Metadata::PolymorphicTypeResolver\>) |  |
| static [GetPropertyName](./getpropertyname/)(ReadStack\&, Utf8JsonReader\&, System::SharedPtr\<JsonSerializerOptions\>, bool\&) |  |
| static [IsMetadataPropertyName](./ismetadatapropertyname/)(ReadOnlySpan\<uint8_t\>, System::SharedPtr\<Serialization::Metadata::PolymorphicTypeResolver\>) |  |
| [JsonSerializer](./jsonserializer/)() |  |
| static [LookupProperty](./lookupproperty/)(System::SharedPtr\<Object\>, ReadOnlySpan\<uint8_t\>, ReadStack\&, System::SharedPtr\<JsonSerializerOptions\>, bool\&, bool) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<Utf8JsonWriter\>, TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [Serialize](./serialize/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [Serialize](./serialize/)(TValue, System::SharedPtr\<JsonSerializerOptions\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [Serialize](./serialize/)(System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [SerializeToDocument](./serializetodocument/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [SerializeToDocument](./serializetodocument/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [SerializeToDocument](./serializetodocument/)(System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [SerializeToElement](./serializetoelement/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [SerializeToElement](./serializetoelement/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [SerializeToElement](./serializetoelement/)(System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [SerializeToNode](./serializetonode/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [SerializeToNode](./serializetonode/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [SerializeToNode](./serializetonode/)(System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [SerializeToUtf8Bytes](./serializetoutf8bytes/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>) |  |
| static [SerializeToUtf8Bytes](./serializetoutf8bytes/)(System::SharedPtr\<Object\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>) |  |
| static [SerializeToUtf8Bytes](./serializetoutf8bytes/)(System::SharedPtr\<Object\>, const TypeInfo\&, System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [TryReadMetadata](./tryreadmetadata/)(System::SharedPtr\<Serialization::JsonConverterBase\>, System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>, Utf8JsonReader\&, ReadStack\&) |  |
| static [ValidateMetadataForArrayConverter](./validatemetadataforarrayconverter/)(System::SharedPtr\<Serialization::JsonConverterBase\>, Utf8JsonReader\&, ReadStack\&) |  |
| static [ValidateMetadataForObjectConverter](./validatemetadataforobjectconverter/)(ReadStack\&) |  |
| static [WriteMetadataForCollection](./writemetadataforcollection/)(System::SharedPtr\<Serialization::JsonConverterBase\>, WriteStack\&, System::SharedPtr\<Utf8JsonWriter\>) |  |
| static [WriteMetadataForObject](./writemetadataforobject/)(System::SharedPtr\<Serialization::JsonConverterBase\>, WriteStack\&, System::SharedPtr\<Utf8JsonWriter\>) |  |
## Fields

| Field | Description |
| --- | --- |
| static [FlushThreshold](./flushthreshold/) |  |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
