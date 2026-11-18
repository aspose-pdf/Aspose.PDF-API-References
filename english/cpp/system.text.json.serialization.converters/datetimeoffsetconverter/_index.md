---
title: System::Text::Json::Serialization::Converters::DateTimeOffsetConverter class
linktitle: DateTimeOffsetConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::DateTimeOffsetConverter class in C++.'
type: docs
weight: 800
url: /cpp/system.text.json.serialization.converters/datetimeoffsetconverter/
---
## DateTimeOffsetConverter class




```cpp
class DateTimeOffsetConverter : public System::Text::Json::Serialization::Converters::JsonPrimitiveConverter<DateTimeOffset>
```

## Methods

| Method | Description |
| --- | --- |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadAsPropertyNameCore](./readaspropertynamecore/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, DateTimeOffset, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteAsPropertyNameCore](./writeaspropertynamecore/)(System::SharedPtr\<Utf8JsonWriter\>, DateTimeOffset, System::SharedPtr\<JsonSerializerOptions\>, bool) override |  |
## See Also

* Class [JsonPrimitiveConverter](../jsonprimitiveconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
