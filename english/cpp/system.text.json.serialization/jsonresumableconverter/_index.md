---
title: System::Text::Json::Serialization::JsonResumableConverter class
linktitle: JsonResumableConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::JsonResumableConverter class in C++.'
type: docs
weight: 1600
url: /cpp/system.text.json.serialization/jsonresumableconverter/
---
## JsonResumableConverter class




```cpp
template<typename T>class JsonResumableConverter : public System::Text::Json::Serialization::JsonConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [get_HandleNull](./get_handlenull/)() override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../jsonconverter/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
