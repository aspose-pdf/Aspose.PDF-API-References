---
title: System::Text::Json::Serialization::JsonDictionaryConverter< TDictionary, TKey, TValue > class
linktitle: JsonDictionaryConverter< TDictionary, TKey, TValue >
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::JsonDictionaryConverter< TDictionary, TKey, TValue > class in C++.'
type: docs
weight: 1300
url: /cpp/system.text.json.serialization/jsondictionaryconverter_tdictionary,tkey,tvalue_/
---
## JsonDictionaryConverter< TDictionary, TKey, TValue > class




```cpp
template<typename TDictionary,typename TKey,typename TValue>class JsonDictionaryConverter< TDictionary, TKey, TValue > : public System::Text::Json::Serialization::JsonDictionaryConverter<TDictionary>
```

## Methods

| Method | Description |
| --- | --- |
| [get_ElementType](./get_elementtype/)() override |  |
| [get_KeyType](./get_keytype/)() override |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, TDictionary\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, TDictionary, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonDictionaryConverter< TDictionary >](../jsondictionaryconverter_tdictionary_/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
