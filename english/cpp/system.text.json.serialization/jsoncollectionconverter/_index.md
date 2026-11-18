---
title: System::Text::Json::Serialization::JsonCollectionConverter class
linktitle: JsonCollectionConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::JsonCollectionConverter class in C++.'
type: docs
weight: 700
url: /cpp/system.text.json.serialization/jsoncollectionconverter/
---
## JsonCollectionConverter class




```cpp
template<typename TCollection,typename TElement>class JsonCollectionConverter : public System::Text::Json::Serialization::JsonResumableConverter<TCollection>
```

## Methods

| Method | Description |
| --- | --- |
| [get_ElementType](./get_elementtype/)() override |  |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, TCollection\&) override |  |
| [OnTryWrite](./ontrywrite/)(System::SharedPtr\<Utf8JsonWriter\>, TCollection, System::SharedPtr\<JsonSerializerOptions\>, WriteStack\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [JsonResumableConverter](../jsonresumableconverter/)
* Namespace [System::Text::Json::Serialization](../)
* Library [Aspose.PDF for C++](../../)
