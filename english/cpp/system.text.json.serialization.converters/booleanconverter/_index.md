---
title: System::Text::Json::Serialization::Converters::BooleanConverter class
linktitle: BooleanConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::BooleanConverter class in C++.'
type: docs
weight: 200
url: /cpp/system.text.json.serialization.converters/booleanconverter/
---
## BooleanConverter class




```cpp
class BooleanConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<bool>
```

## Methods

| Method | Description |
| --- | --- |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, bool, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, bool, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
