---
title: System::Text::Json::Serialization::JsonDictionaryConverter< TDictionary > class
linktitle: JsonDictionaryConverter< TDictionary >
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::JsonDictionaryConverter< TDictionary > class in C++.'
type: docs
weight: 1200
url: /cpp/system.text.json.serialization/jsondictionaryconverter_tdictionary_/
---
## JsonDictionaryConverter< TDictionary > class




```cpp
template<typename TDictionary>class JsonDictionaryConverter< TDictionary > : public System::Text::Json::Serialization::JsonResumableConverter<TDictionary>
```

## Methods

| Method | Description |
| --- | --- |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| virtual [OnWriteResume](./onwriteresume/)(System::SharedPtr\<Utf8JsonWriter\>, TDictionary, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonResumableConverter](../jsonresumableconverter/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
