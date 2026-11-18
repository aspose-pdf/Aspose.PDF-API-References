---
title: System::Text::Json::Serialization::Converters::JsonMetadataServicesConverter class
linktitle: JsonMetadataServicesConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::JsonMetadataServicesConverter class in C++.'
type: docs
weight: 3100
url: /cpp/system.text.json.serialization.converters/jsonmetadataservicesconverter/
---
## JsonMetadataServicesConverter class




```cpp
template<typename T>class JsonMetadataServicesConverter : public System::Text::Json::Serialization::JsonResumableConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanHaveMetadata](./get_canhavemetadata/)() override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [get_ConstructorIsParameterized](./get_constructorisparameterized/)() override |  |
| [get_Converter](./get_converter/)() |  |
| [get_ElementType](./get_elementtype/)() override |  |
| [get_HandleNull](./get_handlenull/)() override |  |
| [get_KeyType](./get_keytype/)() override |  |
| [get_NullableElementConverter](./get_nullableelementconverter/)() override |  |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [JsonMetadataServicesConverter](./jsonmetadataservicesconverter/)(System::SharedPtr\<JsonConverter\<T\>\>) |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, T\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, T, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonResumableConverter](../../system.text.json.serialization/jsonresumableconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
