---
title: System::Text::Json::Serialization::Metadata::JsonCollectionInfoValues class
linktitle: JsonCollectionInfoValues
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::JsonCollectionInfoValues class in C++.'
type: docs
weight: 400
url: /cpp/system.text.json.serialization.metadata/jsoncollectioninfovalues/
---
## JsonCollectionInfoValues class




```cpp
template<typename TCollection>class JsonCollectionInfoValues : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ElementInfo](./get_elementinfo/)() |  |
| [get_FastObjectCreator](./get_fastobjectcreator/)() const |  |
| [get_FastSerializeContext](./get_fastserializecontext/)() const |  |
| [get_FastSerializeHandler](./get_fastserializehandler/)() const |  |
| [get_KeyInfo](./get_keyinfo/)() |  |
| [get_NumberHandling](./get_numberhandling/)() |  |
| [get_ObjectCreator](./get_objectcreator/)() |  |
| [get_PolymorphismOptions](./get_polymorphismoptions/)() |  |
| [get_SerializeHandler](./get_serializehandler/)() |  |
| [get_TypeClassifierFactory](./get_typeclassifierfactory/)() |  |
| [init_ElementInfo](./init_elementinfo/)(System::SharedPtr\<JsonTypeInfoBase\>) |  |
| [init_KeyInfo](./init_keyinfo/)(System::SharedPtr\<JsonTypeInfoBase\>) |  |
| [init_NumberHandling](./init_numberhandling/)(JsonNumberHandling) |  |
| [init_ObjectCreator](./init_objectcreator/)(Func\<TCollection\>) |  |
| [init_ObjectCreatorFast](./init_objectcreatorfast/)(ObjectCreatorFn) |  |
| [init_PolymorphismOptions](./init_polymorphismoptions/)(System::SharedPtr\<JsonPolymorphismOptions\>) |  |
| [init_SerializeHandler](./init_serializehandler/)(Action\<System::SharedPtr\<Utf8JsonWriter\>, TCollection\>) |  |
| [init_SerializeHandlerFast](./init_serializehandlerfast/)(SerializeHandlerFn, void *) |  |
| [init_TypeClassifierFactory](./init_typeclassifierfactory/)(System::SharedPtr\<JsonTypeClassifierFactoryBase\>) |  |
| [JsonCollectionInfoValues](./jsoncollectioninfovalues/)() |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ObjectCreatorFn](./objectcreatorfn/) |  |
| [SerializeHandlerFn](./serializehandlerfn/) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
