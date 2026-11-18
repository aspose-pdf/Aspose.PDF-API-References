---
title: System::Text::Json::Serialization::Metadata::JsonTypeInfo class
linktitle: JsonTypeInfo
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::JsonTypeInfo class in C++.'
type: docs
weight: 1500
url: /cpp/system.text.json.serialization.metadata/jsontypeinfo/
---
## JsonTypeInfo class




```cpp
template<typename T>class JsonTypeInfo : public System::Text::Json::Serialization::Metadata::JsonTypeInfoBase
```

## Methods

| Method | Description |
| --- | --- |
| [CreateObjectInstance](../jsontypeinfobase/createobjectinstance/)() |  |
| [get_Converter](../jsontypeinfobase/get_converter/)() |  |
| [get_CreateObject](./get_createobject/)() |  |
| [get_ElementType](../jsontypeinfobase/get_elementtype/)() |  |
| [get_FastCreateObject](../jsontypeinfobase/get_fastcreateobject/)() const |  |
| [get_FastSerializeContext](./get_fastserializecontext/)() const |  |
| [get_FastSerializeHandler](./get_fastserializehandler/)() const |  |
| [get_HasCreateObject](../jsontypeinfobase/get_hascreateobject/)() |  |
| [get_IsReadOnly](../jsontypeinfobase/get_isreadonly/)() |  |
| [get_KeyType](../jsontypeinfobase/get_keytype/)() |  |
| [get_Kind](../jsontypeinfobase/get_kind/)() |  |
| [get_NumberHandling](../jsontypeinfobase/get_numberhandling/)() |  |
| [get_OnDeserialized](../jsontypeinfobase/get_ondeserialized/)() |  |
| [get_OnDeserializing](../jsontypeinfobase/get_ondeserializing/)() |  |
| [get_OnSerialized](../jsontypeinfobase/get_onserialized/)() |  |
| [get_OnSerializing](../jsontypeinfobase/get_onserializing/)() |  |
| [get_Options](../jsontypeinfobase/get_options/)() |  |
| [get_OriginatingResolver](../jsontypeinfobase/get_originatingresolver/)() |  |
| [get_PolymorphismOptions](../jsontypeinfobase/get_polymorphismoptions/)() |  |
| [get_Properties](../jsontypeinfobase/get_properties/)() |  |
| [get_SerializeHandler](./get_serializehandler/)() |  |
| [get_Type](../jsontypeinfobase/get_type/)() |  |
| [get_TypeClassifier](../jsontypeinfobase/get_typeclassifier/)() |  |
| [InvokeOnDeserialized](../jsontypeinfobase/invokeondeserialized/)(System::SharedPtr\<Object\>) |  |
| [InvokeOnDeserializing](../jsontypeinfobase/invokeondeserializing/)(System::SharedPtr\<Object\>) |  |
| [InvokeOnSerialized](../jsontypeinfobase/invokeonserialized/)(System::SharedPtr\<Object\>) |  |
| [InvokeOnSerializing](../jsontypeinfobase/invokeonserializing/)(System::SharedPtr\<Object\>) |  |
| [InvokeSerializeHandler](./invokeserializehandler/)(System::SharedPtr\<Utf8JsonWriter\>, const T\&) |  |
| [MakeReadOnly](../jsontypeinfobase/makereadonly/)() |  |
| [set_CreateObject](./set_createobject/)(Func\<T\>) |  |
| [set_CreateObject](../jsontypeinfobase/set_createobject/)(Func\<System::SharedPtr\<Object\>\>) |  |
| [set_FastCreateObject](../jsontypeinfobase/set_fastcreateobject/)(ObjectCreatorFn) |  |
| [set_FastOnDeserialized](../jsontypeinfobase/set_fastondeserialized/)(ObjectCallbackFn) |  |
| [set_FastOnDeserializing](../jsontypeinfobase/set_fastondeserializing/)(ObjectCallbackFn) |  |
| [set_FastOnSerialized](../jsontypeinfobase/set_fastonserialized/)(ObjectCallbackFn) |  |
| [set_FastOnSerializing](../jsontypeinfobase/set_fastonserializing/)(ObjectCallbackFn) |  |
| [set_FastSerializeHandler](./set_fastserializehandler/)(FastSerializeHandlerFn, void *) |  |
| [set_NumberHandling](../jsontypeinfobase/set_numberhandling/)(Nullable\<JsonNumberHandling\>) |  |
| [set_OnDeserialized](../jsontypeinfobase/set_ondeserialized/)(Action\<System::SharedPtr\<Object\>\>) |  |
| [set_OnDeserializing](../jsontypeinfobase/set_ondeserializing/)(Action\<System::SharedPtr\<Object\>\>) |  |
| [set_OnSerialized](../jsontypeinfobase/set_onserialized/)(Action\<System::SharedPtr\<Object\>\>) |  |
| [set_OnSerializing](../jsontypeinfobase/set_onserializing/)(Action\<System::SharedPtr\<Object\>\>) |  |
| [set_OriginatingResolver](../jsontypeinfobase/set_originatingresolver/)(System::SharedPtr\<IJsonTypeInfoResolver\>) |  |
| [set_PolymorphismOptions](../jsontypeinfobase/set_polymorphismoptions/)(System::SharedPtr\<JsonPolymorphismOptions\>) |  |
| [set_TypeClassifier](../jsontypeinfobase/set_typeclassifier/)(JsonTypeClassifier) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [FastSerializeHandlerFn](./fastserializehandlerfn/) |  |
## See Also

* Class [JsonTypeInfoBase](../jsontypeinfobase/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
