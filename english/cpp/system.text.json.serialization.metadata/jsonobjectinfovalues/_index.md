---
title: System::Text::Json::Serialization::Metadata::JsonObjectInfoValues class
linktitle: JsonObjectInfoValues
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::JsonObjectInfoValues class in C++.'
type: docs
weight: 700
url: /cpp/system.text.json.serialization.metadata/jsonobjectinfovalues/
---
## JsonObjectInfoValues class




```cpp
template<typename T>class JsonObjectInfoValues : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ConstructorParameterMetadataInitializer](./get_constructorparametermetadatainitializer/)() |  |
| [get_FastObjectCreator](./get_fastobjectcreator/)() const |  |
| [get_FastPropertyMetadataInitializer](./get_fastpropertymetadatainitializer/)() const |  |
| [get_FastSerializeContext](./get_fastserializecontext/)() const |  |
| [get_FastSerializeHandler](./get_fastserializehandler/)() const |  |
| [get_NumberHandling](./get_numberhandling/)() |  |
| [get_ObjectCreator](./get_objectcreator/)() |  |
| [get_ObjectWithParameterizedConstructorCreator](./get_objectwithparameterizedconstructorcreator/)() |  |
| [get_PolymorphismOptions](./get_polymorphismoptions/)() |  |
| [get_PropertyMetadataInitializer](./get_propertymetadatainitializer/)() |  |
| [get_SerializeHandler](./get_serializehandler/)() |  |
| [get_TypeClassifierFactory](./get_typeclassifierfactory/)() |  |
| [init_ConstructorParameterMetadataInitializer](./init_constructorparametermetadatainitializer/)(Func\<System::SharedPtr\<Array\<System::SharedPtr\<JsonParameterInfoValues\>\>\>\>) |  |
| [init_NumberHandling](./init_numberhandling/)(JsonNumberHandling) |  |
| [init_ObjectCreator](./init_objectcreator/)(Func\<T\>) |  |
| [init_ObjectCreatorFast](./init_objectcreatorfast/)(ObjectCreatorFn) |  |
| [init_ObjectWithParameterizedConstructorCreator](./init_objectwithparameterizedconstructorcreator/)(Func\<System::SharedPtr\<Array\<System::SharedPtr\<Object\>\>\>, T\>) |  |
| [init_PolymorphismOptions](./init_polymorphismoptions/)(System::SharedPtr\<JsonPolymorphismOptions\>) |  |
| [init_PropertyMetadataInitializer](./init_propertymetadatainitializer/)(Func\<System::SharedPtr\<JsonSerializerContext\>, System::SharedPtr\<Array\<System::SharedPtr\<JsonPropertyInfoBase\>\>\>\>) |  |
| [init_PropertyMetadataInitializerFast](./init_propertymetadatainitializerfast/)(PropertyMetadataInitializerFn) |  |
| [init_SerializeHandler](./init_serializehandler/)(Action\<System::SharedPtr\<Utf8JsonWriter\>, T\>) |  |
| [init_SerializeHandlerFast](./init_serializehandlerfast/)(SerializeHandlerFn, void *) |  |
| [init_TypeClassifierFactory](./init_typeclassifierfactory/)(System::SharedPtr\<JsonTypeClassifierFactoryBase\>) |  |
| [JsonObjectInfoValues](./jsonobjectinfovalues/)(Func\<T\>, Func\<System::SharedPtr\<Array\<System::SharedPtr\<Object\>\>\>, T\>, Func\<System::SharedPtr\<JsonSerializerContext\>, System::SharedPtr\<Array\<System::SharedPtr\<JsonPropertyInfoBase\>\>\>\>, Func\<System::SharedPtr\<Array\<System::SharedPtr\<JsonParameterInfoValues\>\>\>\>, JsonNumberHandling, System::SharedPtr\<JsonPolymorphismOptions\>, Action\<System::SharedPtr\<Utf8JsonWriter\>, T\>, System::SharedPtr\<JsonTypeClassifierFactoryBase\>) |  |
| [JsonObjectInfoValues](./jsonobjectinfovalues/)() |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ObjectCreatorFn](./objectcreatorfn/) |  |
| [PropertyMetadataInitializerFn](./propertymetadatainitializerfn/) |  |
| [SerializeHandlerFn](./serializehandlerfn/) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
