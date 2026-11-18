---
title: System::Text::Json::Serialization::Converters::MemoryByteConverter class
linktitle: MemoryByteConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::MemoryByteConverter class in C++.'
type: docs
weight: 3800
url: /cpp/system.text.json.serialization.converters/memorybyteconverter/
---
## MemoryByteConverter class




```cpp
class MemoryByteConverter : public System::Text::Json::Serialization::JsonConverter<Memory<uint8_t>>
```

## Methods

| Method | Description |
| --- | --- |
| [get_HandleNull](./get_handlenull/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, Memory\<uint8_t\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
