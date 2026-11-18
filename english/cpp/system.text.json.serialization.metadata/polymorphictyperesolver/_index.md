---
title: System::Text::Json::Serialization::Metadata::PolymorphicTypeResolver class
linktitle: PolymorphicTypeResolver
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::PolymorphicTypeResolver class in C++.'
type: docs
weight: 2000
url: /cpp/system.text.json.serialization.metadata/polymorphictyperesolver/
---
## PolymorphicTypeResolver class




```cpp
class PolymorphicTypeResolver : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [FindNearestPolymorphicBaseType](./findnearestpolymorphicbasetype/)(System::SharedPtr\<JsonTypeInfoBase\>) |  |
| [get_BaseType](./get_basetype/)() |  |
| [get_CustomTypeDiscriminatorPropertyNameJsonEncoded](./get_customtypediscriminatorpropertynamejsonencoded/)() |  |
| [get_CustomTypeDiscriminatorPropertyNameUtf8](./get_customtypediscriminatorpropertynameutf8/)() |  |
| [get_IgnoreUnrecognizedTypeDiscriminators](./get_ignoreunrecognizedtypediscriminators/)() |  |
| [get_UnknownDerivedTypeHandling](./get_unknownderivedtypehandling/)() |  |
| [get_UsesTypeDiscriminators](./get_usestypediscriminators/)() |  |
| static [IsSupportedDerivedType](./issupportedderivedtype/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [IsSupportedPolymorphicBaseType](./issupportedpolymorphicbasetype/)(const TypeInfo\&) |  |
| [PolymorphicTypeResolver](./polymorphictyperesolver/)(System::SharedPtr\<JsonSerializerOptions\>, System::SharedPtr\<JsonPolymorphismOptions\>, const TypeInfo\&, bool) |  |
| [TryGetDerivedJsonTypeInfo](./trygetderivedjsontypeinfo/)(const TypeInfo\&, System::SharedPtr\<JsonTypeInfoBase\>\&, System::SharedPtr\<Object\>\&) |  |
| [TryGetDerivedJsonTypeInfo](./trygetderivedjsontypeinfo/)(System::SharedPtr\<Object\>, System::SharedPtr\<JsonTypeInfoBase\>\&) |  |
| [TryResolveDerivedJsonTypeInfo](./tryresolvederivedjsontypeinfo/)(const TypeInfo\&, System::SharedPtr\<JsonTypeInfoBase\>\&) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
