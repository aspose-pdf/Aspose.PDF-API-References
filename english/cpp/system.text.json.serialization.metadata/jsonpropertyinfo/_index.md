---
title: System::Text::Json::Serialization::Metadata::JsonPropertyInfo class
linktitle: JsonPropertyInfo
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::JsonPropertyInfo class in C++.'
type: docs
weight: 1200
url: /cpp/system.text.json.serialization.metadata/jsonpropertyinfo/
---
## JsonPropertyInfo class




```cpp
template<typename T>class JsonPropertyInfo : public System::Text::Json::Serialization::Metadata::JsonPropertyInfoBase
```

## Methods

| Method | Description |
| --- | --- |
| [AddJsonParameterInfo](./addjsonparameterinfo/)(System::SharedPtr\<JsonParameterInfoValues\>) override |  |
| [get_AssociatedParameter](../jsonpropertyinfobase/get_associatedparameter/)() |  |
| [get_CustomConverter](../jsonpropertyinfobase/get_customconverter/)() |  |
| [get_DeclaringType](../jsonpropertyinfobase/get_declaringtype/)() |  |
| [get_DefaultValue](./get_defaultvalue/)() override |  |
| [get_EffectiveConverter](./get_effectiveconverter/)() |  |
| [get_FastGetter](./get_fastgetter/)() const |  |
| [get_FastSetter](./get_fastsetter/)() const |  |
| [get_FastShouldSerialize](./get_fastshouldserialize/)() const |  |
| [get_Get](./get_get/)() |  |
| [get_IsExtensionData](../jsonpropertyinfobase/get_isextensiondata/)() |  |
| [get_IsGetNullable](../jsonpropertyinfobase/get_isgetnullable/)() |  |
| [get_IsRequired](../jsonpropertyinfobase/get_isrequired/)() |  |
| [get_IsSetNullable](../jsonpropertyinfobase/get_issetnullable/)() |  |
| [get_Name](../jsonpropertyinfobase/get_name/)() |  |
| [get_NumberHandling](../jsonpropertyinfobase/get_numberhandling/)() |  |
| [get_Options](../jsonpropertyinfobase/get_options/)() |  |
| [get_Order](../jsonpropertyinfobase/get_order/)() |  |
| [get_PropertyType](../jsonpropertyinfobase/get_propertytype/)() |  |
| [get_PropertyTypeCanBeNull](./get_propertytypecanbenull/)() override |  |
| [get_Set](./get_set/)() |  |
| [get_ShouldSerialize](./get_shouldserialize/)() |  |
| [GetMemberAndWriteJson](./getmemberandwritejson/)(System::SharedPtr\<Object\>, WriteStack\&, System::SharedPtr\<Utf8JsonWriter\>) override |  |
| [GetMemberAndWriteJsonExtensionData](./getmemberandwritejsonextensiondata/)(System::SharedPtr\<Object\>, WriteStack\&, System::SharedPtr\<Utf8JsonWriter\>) override |  |
| [GetValueAsObject](./getvalueasobject/)(System::SharedPtr\<Object\>) override |  |
| [JsonPropertyInfo](./jsonpropertyinfo/)(const TypeInfo\&, System::SharedPtr\<System::Text::Json::Serialization::Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) |  |
| [ReadJsonAndSetMember](./readjsonandsetmember/)(System::SharedPtr\<Object\>, ReadStack\&, Utf8JsonReader\&) override |  |
| [ReadJsonAsObject](./readjsonasobject/)(ReadStack\&, Utf8JsonReader\&, System::SharedPtr\<Object\>\&) override |  |
| [set_CustomConverter](../jsonpropertyinfobase/set_customconverter/)(System::SharedPtr\<JsonConverterBase\>) |  |
| [set_Get](./set_get/)(Func\<System::SharedPtr\<Object\>, T\>) |  |
| [set_Get](../jsonpropertyinfobase/set_get/)(Func\<System::SharedPtr\<Object\>, System::SharedPtr\<Object\>\>) |  |
| [set_GetFast](./set_getfast/)(GetterFn) |  |
| [set_IsExtensionData](../jsonpropertyinfobase/set_isextensiondata/)(bool) |  |
| [set_IsGetNullable](../jsonpropertyinfobase/set_isgetnullable/)(bool) |  |
| [set_IsRequired](../jsonpropertyinfobase/set_isrequired/)(bool) |  |
| [set_IsSetNullable](../jsonpropertyinfobase/set_issetnullable/)(bool) |  |
| [set_Name](../jsonpropertyinfobase/set_name/)(String) |  |
| [set_NumberHandling](../jsonpropertyinfobase/set_numberhandling/)(Nullable\<JsonNumberHandling\>) |  |
| [set_Order](../jsonpropertyinfobase/set_order/)(int32_t) |  |
| [set_Set](./set_set/)(Action\<System::SharedPtr\<Object\>, T\>) |  |
| [set_Set](../jsonpropertyinfobase/set_set/)(Action\<System::SharedPtr\<Object\>, System::SharedPtr\<Object\>\>) |  |
| [set_SetFast](./set_setfast/)(SetterFn) |  |
| [set_ShouldSerialize](./set_shouldserialize/)(Func\<System::SharedPtr\<Object\>, T, bool\>) |  |
| [set_ShouldSerialize](../jsonpropertyinfobase/set_shouldserialize/)(Func\<System::SharedPtr\<Object\>, System::SharedPtr\<Object\>, bool\>) |  |
| [set_ShouldSerializeFast](./set_shouldserializefast/)(ShouldSerializeFn) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [GetterFn](./getterfn/) |  |
| [SetterFn](./setterfn/) |  |
| [ShouldSerializeFn](./shouldserializefn/) |  |
## See Also

* Class [JsonPropertyInfoBase](../jsonpropertyinfobase/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
