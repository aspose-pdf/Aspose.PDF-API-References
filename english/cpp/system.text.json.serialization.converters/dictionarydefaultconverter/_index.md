---
title: System::Text::Json::Serialization::Converters::DictionaryDefaultConverter class
linktitle: DictionaryDefaultConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::DictionaryDefaultConverter class in C++.'
type: docs
weight: 1100
url: /cpp/system.text.json.serialization.converters/dictionarydefaultconverter/
---
## DictionaryDefaultConverter class




```cpp
template<typename TDictionary,typename TKey,typename TValue>class DictionaryDefaultConverter : public System::Text::Json::Serialization::JsonDictionaryConverter<TDictionary, TKey, TValue>
```

## Methods

| Method | Description |
| --- | --- |
| [get_CanHaveMetadata](./get_canhavemetadata/)() override |  |
| [OnWriteResume](./onwriteresume/)(System::SharedPtr\<Utf8JsonWriter\>, TDictionary, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonDictionaryConverter< TDictionary, TKey, TValue >](../../system.text.json.serialization/jsondictionaryconverter_tdictionary,tkey,tvalue_/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
