---
title: System::Text::Json::Serialization::Converters::ByteArrayConverter class
linktitle: ByteArrayConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ByteArrayConverter class in C++.'
type: docs
weight: 300
url: /cpp/system.text.json.serialization.converters/bytearrayconverter/
---
## ByteArrayConverter class




```cpp
class ByteArrayConverter : public System::Text::Json::Serialization::JsonConverter<System::SharedPtr<Array<uint8_t>>>
```

## Methods

| Method | Description |
| --- | --- |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<Array\<uint8_t\>\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
