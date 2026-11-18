---
title: System::Text::Json::Serialization::Converters::IListConverter class
linktitle: IListConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::IListConverter class in C++.'
type: docs
weight: 2200
url: /cpp/system.text.json.serialization.converters/ilistconverter/
---
## IListConverter class




```cpp
template<typename TCollection>class IListConverter : public System::Text::Json::Serialization::JsonCollectionConverter<TCollection, System::SharedPtr<Object>>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonCollectionConverter](../../system.text.json.serialization/jsoncollectionconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
