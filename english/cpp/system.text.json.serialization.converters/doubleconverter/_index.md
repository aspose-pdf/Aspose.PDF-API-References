---
title: System::Text::Json::Serialization::Converters::DoubleConverter class
linktitle: DoubleConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::DoubleConverter class in C++.'
type: docs
weight: 1300
url: /cpp/system.text.json.serialization.converters/doubleconverter/
---
## DoubleConverter class




```cpp
class DoubleConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<double>
```

## Methods

| Method | Description |
| --- | --- |
| [DoubleConverter](./doubleconverter/)() |  |
| [get_IsIeeeFloatingPointConverter](./get_isieeefloatingpointconverter/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadNumberWithCustomHandling](./readnumberwithcustomhandling/)(Utf8JsonReader\&, JsonNumberHandling, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, double, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, double, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
| [WriteNumberWithCustomHandling](./writenumberwithcustomhandling/)(System::SharedPtr\<Utf8JsonWriter\>, double, JsonNumberHandling) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
