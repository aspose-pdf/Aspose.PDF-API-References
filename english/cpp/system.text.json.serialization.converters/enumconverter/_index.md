---
title: System::Text::Json::Serialization::Converters::EnumConverter class
linktitle: EnumConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::EnumConverter class in C++.'
type: docs
weight: 1400
url: /cpp/system.text.json.serialization.converters/enumconverter/
---
## EnumConverter class




```cpp
template<typename T>class EnumConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [EnumConverter](./enumconverter/)(EnumConverterOptions, System::SharedPtr\<JsonNamingPolicy\>, System::SharedPtr\<JsonSerializerOptions\>) |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
