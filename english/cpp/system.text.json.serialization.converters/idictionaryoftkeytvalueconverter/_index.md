---
title: System::Text::Json::Serialization::Converters::IDictionaryOfTKeyTValueConverter class
linktitle: IDictionaryOfTKeyTValueConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::IDictionaryOfTKeyTValueConverter class in C++.'
type: docs
weight: 1800
url: /cpp/system.text.json.serialization.converters/idictionaryoftkeytvalueconverter/
---
## IDictionaryOfTKeyTValueConverter class




```cpp
template<typename TDictionary,typename TKey,typename TValue>class IDictionaryOfTKeyTValueConverter : public System::Text::Json::Serialization::Converters::DictionaryDefaultConverter<TDictionary, TKey, TValue>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [DictionaryDefaultConverter](../dictionarydefaultconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
