---
title: System::Text::Json::Serialization::Converters::JsonDocumentConverter class
linktitle: JsonDocumentConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonDocumentConverter class in C++.'
type: docs
weight: 2900
url: /cpp/system.text.json.serialization.converters/jsondocumentconverter/
---
## JsonDocumentConverter class




```cpp
class JsonDocumentConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<JsonDocument>>
```

## Methods

| Method | Description |
| --- | --- |
| [get_HandleNull](./get_handlenull/)() override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<JsonDocument\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
