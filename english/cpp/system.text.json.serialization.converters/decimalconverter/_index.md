---
title: System::Text::Json::Serialization::Converters::DecimalConverter class
linktitle: DecimalConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::DecimalConverter class in C++.'
type: docs
weight: 900
url: /cpp/system.text.json.serialization.converters/decimalconverter/
---
## DecimalConverter class




```cpp
class DecimalConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<Decimal>
```

## Methods

| Method | Description |
| --- | --- |
| [DecimalConverter](./decimalconverter/)() |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadNumberWithCustomHandling](./readnumberwithcustomhandling/)(Utf8JsonReader\&, JsonNumberHandling, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, Decimal, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, Decimal, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
| [WriteNumberWithCustomHandling](./writenumberwithcustomhandling/)(System::SharedPtr\<Utf8JsonWriter\>, Decimal, JsonNumberHandling) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
