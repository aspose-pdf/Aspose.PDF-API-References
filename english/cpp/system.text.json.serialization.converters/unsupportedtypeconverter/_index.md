---
title: System::Text::Json::Serialization::Converters::UnsupportedTypeConverter class
linktitle: UnsupportedTypeConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::UnsupportedTypeConverter class in C++.'
type: docs
weight: 5500
url: /cpp/system.text.json.serialization.converters/unsupportedtypeconverter/
---
## UnsupportedTypeConverter class




```cpp
template<typename T>class UnsupportedTypeConverter : public System::Text::Json::Serialization::JsonConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [get_ErrorMessage](./get_errormessage/)() |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [UnsupportedTypeConverter](./unsupportedtypeconverter/)(String) |  |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
