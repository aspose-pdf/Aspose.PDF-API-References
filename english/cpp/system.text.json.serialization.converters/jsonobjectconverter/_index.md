---
title: System::Text::Json::Serialization::Converters::JsonObjectConverter class
linktitle: JsonObjectConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonObjectConverter class in C++.'
type: docs
weight: 3300
url: /cpp/system.text.json.serialization.converters/jsonobjectconverter/
---
## JsonObjectConverter class




```cpp
class JsonObjectConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<Nodes::JsonObject>>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| static [ReadAsJsonElement](./readasjsonelement/)(Utf8JsonReader\&, Nodes::JsonNodeOptions) |  |
| static [ReadAsJsonNode](./readasjsonnode/)(Utf8JsonReader\&, Nodes::JsonNodeOptions) |  |
| [ReadElementAndSetProperty](./readelementandsetproperty/)(System::SharedPtr\<Object\>, String, Utf8JsonReader\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Nodes::JsonObject\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteExtensionDataValue](./writeextensiondatavalue/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Nodes::JsonObject\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
