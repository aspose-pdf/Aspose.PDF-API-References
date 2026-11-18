---
title: System::Text::Json::Serialization::Converters::CastingConverter class
linktitle: CastingConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::CastingConverter class in C++.'
type: docs
weight: 500
url: /cpp/system.text.json.serialization.converters/castingconverter/
---
## CastingConverter class




```cpp
template<typename T>class CastingConverter : public System::Text::Json::Serialization::JsonConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [CastingConverter](./castingconverter/)(System::SharedPtr\<JsonConverterBase\>) |  |
| [get_ElementType](./get_elementtype/)() override |  |
| [get_HandleNull](./get_handlenull/)() override |  |
| [get_KeyType](./get_keytype/)() override |  |
| [get_NullableElementConverter](./get_nullableelementconverter/)() override |  |
| [get_SourceConverterForCastingConverter](./get_sourceconverterforcastingconverter/)() override |  |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, T\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyName](./readaspropertyname/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadNumberWithCustomHandling](./readnumberwithcustomhandling/)(Utf8JsonReader\&, JsonNumberHandling, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyName](./writeaspropertyname/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
| [WriteNumberWithCustomHandling](./writenumberwithcustomhandling/)(System::SharedPtr\<Utf8JsonWriter\>, T, JsonNumberHandling) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
