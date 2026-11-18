---
title: System::Text::Json::Serialization::Converters::ObjectDefaultConverter class
linktitle: ObjectDefaultConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ObjectDefaultConverter class in C++.'
type: docs
weight: 4100
url: /cpp/system.text.json.serialization.converters/objectdefaultconverter/
---
## ObjectDefaultConverter class




```cpp
template<typename T>class ObjectDefaultConverter : public System::Text::Json::Serialization::JsonObjectConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [get_CanHaveMetadata](./get_canhavemetadata/)() override |  |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, T\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| static [PopulatePropertiesFastPath](./populatepropertiesfastpath/)(System::SharedPtr\<Object\>, System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>, Utf8JsonReader\&, ReadStack\&) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonObjectConverter](../../system.text.json.serialization/jsonobjectconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
