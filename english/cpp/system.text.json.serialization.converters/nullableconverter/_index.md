---
title: System::Text::Json::Serialization::Converters::NullableConverter class
linktitle: NullableConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::NullableConverter class in C++.'
type: docs
weight: 3900
url: /cpp/system.text.json.serialization.converters/nullableconverter/
---
## NullableConverter class




```cpp
template<typename T>class NullableConverter : public System::Text::Json::Serialization::JsonConverter<Nullable<T>>
```

## Methods

| Method | Description |
| --- | --- |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [get_ConstructorIsParameterized](./get_constructorisparameterized/)() override |  |
| [get_ElementType](./get_elementtype/)() override |  |
| [get_HandleNull](./get_handlenull/)() override |  |
| [get_NullableElementConverter](./get_nullableelementconverter/)() override |  |
| [GetSupportedJsonValueTypes](./getsupportedjsonvaluetypes/)(JsonNumberHandling) override |  |
| [NullableConverter](./nullableconverter/)(System::SharedPtr\<JsonConverter\<T\>\>) |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, Nullable\<T\>\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, Nullable\<T\>, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [Read](./read/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [ReadNumberWithCustomHandling](./readnumberwithcustomhandling/)(Utf8JsonReader\&, JsonNumberHandling, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [Write](./write/)(System::SharedPtr\<Utf8JsonWriter\>, Nullable\<T\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [WriteNumberWithCustomHandling](./writenumberwithcustomhandling/)(System::SharedPtr\<Utf8JsonWriter\>, Nullable\<T\>, JsonNumberHandling) override |  |
## See Also

* Class [JsonConverter](../../system.text.json.serialization/jsonconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
