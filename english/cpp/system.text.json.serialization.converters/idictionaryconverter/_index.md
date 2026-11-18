---
title: System::Text::Json::Serialization::Converters::IDictionaryConverter class
linktitle: IDictionaryConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::IDictionaryConverter class in C++.'
type: docs
weight: 1700
url: /cpp/system.text.json.serialization.converters/idictionaryconverter/
---
## IDictionaryConverter class




```cpp
template<typename TDictionary>class IDictionaryConverter : public System::Text::Json::Serialization::JsonDictionaryConverter<TDictionary, String, System::SharedPtr<Object>>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [OnWriteResume](./onwriteresume/)(System::SharedPtr\<Utf8JsonWriter\>, TDictionary, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override |  |
## See Also

* Class [JsonDictionaryConverter](../../system.text.json.serialization/jsondictionaryconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
