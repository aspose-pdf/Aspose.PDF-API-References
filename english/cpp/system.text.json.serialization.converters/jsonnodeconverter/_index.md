---
title: System::Text::Json::Serialization::Converters::JsonNodeConverter class
linktitle: JsonNodeConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonNodeConverter class in C++.'
type: docs
weight: 3200
url: /cpp/system.text.json.serialization.converters/jsonnodeconverter/
---
## JsonNodeConverter class




```cpp
class JsonNodeConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<Nodes::JsonNode>>
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)(JsonElement, Nullable\<Nodes::JsonNodeOptions\>) |  |
| static [get_Instance](./get_instance/)() |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| static [ReadAsJsonElement](./readasjsonelement/)(Utf8JsonReader\&, Nodes::JsonNodeOptions) |  |
| static [ReadAsJsonNode](./readasjsonnode/)(Utf8JsonReader\&, Nodes::JsonNodeOptions) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Nodes::JsonNode\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
