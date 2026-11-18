---
title: System::Text::Json::Serialization::Converters::ObjectConverter class
linktitle: ObjectConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ObjectConverter class in C++.'
type: docs
weight: 4000
url: /cpp/system.text.json.serialization.converters/objectconverter/
---
## ObjectConverter class




```cpp
class ObjectConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<Object>>
```

## Methods

| Method | Description |
| --- | --- |
| [ObjectConverter](./objectconverter/)() |  |
| [ReadAsPropertyName](./readaspropertyname/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyName](./writeaspropertyname/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
