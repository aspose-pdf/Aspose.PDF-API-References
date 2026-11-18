---
title: System::Text::Json::Serialization::Converters::SingleConverter class
linktitle: SingleConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::SingleConverter class in C++.'
type: docs
weight: 4600
url: /cpp/system.text.json.serialization.converters/singleconverter/
---
## SingleConverter class




```cpp
class SingleConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<float>
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsIeeeFloatingPointConverter](./get_isieeefloatingpointconverter/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadNumberWithCustomHandling](./readnumberwithcustomhandling/)(Utf8JsonReader\&, JsonNumberHandling, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [SingleConverter](./singleconverter/)() |  |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, float, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, float, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
| [WriteNumberWithCustomHandling](./writenumberwithcustomhandling/)(System::SharedPtr\<Utf8JsonWriter\>, float, JsonNumberHandling) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
