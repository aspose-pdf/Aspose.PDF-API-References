---
title: System::Text::Json::Serialization::Converters::JsonPrimitiveConverter class
linktitle: JsonPrimitiveConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonPrimitiveConverter class in C++.'
type: docs
weight: 3400
url: /cpp/system.text.json.serialization.converters/jsonprimitiveconverter/
---
## JsonPrimitiveConverter class




```cpp
template<typename T>class JsonPrimitiveConverter : public System::Text::Json::Serialization::JsonConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [ReadAsPropertyName](./readaspropertyname/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [WriteAsPropertyName](./writeaspropertyname/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
