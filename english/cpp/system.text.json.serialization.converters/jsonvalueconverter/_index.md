---
title: System::Text::Json::Serialization::Converters::JsonValueConverter class
linktitle: JsonValueConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonValueConverter class in C++.'
type: docs
weight: 3500
url: /cpp/system.text.json.serialization.converters/jsonvalueconverter/
---
## JsonValueConverter class




```cpp
class JsonValueConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<Nodes::JsonValueBase>>
```

## Methods

| Method | Description |
| --- | --- |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| static [ReadNonNullPrimitiveValue](./readnonnullprimitivevalue/)(Utf8JsonReader\&, Nodes::JsonNodeOptions) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Nodes::JsonValueBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
