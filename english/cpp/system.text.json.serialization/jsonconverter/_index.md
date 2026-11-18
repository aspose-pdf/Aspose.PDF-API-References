---
title: System::Text::Json::Serialization::JsonConverter class
linktitle: JsonConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::JsonConverter class in C++.'
type: docs
weight: 800
url: /cpp/system.text.json.serialization/jsonconverter/
---
## JsonConverter class




```cpp
template<typename T>class JsonConverter : public System::Text::Json::Serialization::JsonConverterBase
```

## Methods

| Method | Description |
| --- | --- |
| [CanConvert](./canconvert/)(const System::TypeInfo\&) override |  |
| virtual [get_HandleNull](./get_handlenull/)() |  |
| [get_Type](./get_type/)() override |  |
| virtual [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) |  |
| virtual [ReadAsPropertyName](./readaspropertyname/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| virtual [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) |  |
| virtual [WriteAsPropertyName](./writeaspropertyname/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) |  |
## See Also

* Class [JsonConverterBase](../jsonconverterbase/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
