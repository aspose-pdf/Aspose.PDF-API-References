---
title: System::Text::Json::Serialization::Metadata::JsonTypeInfoResolverChain class
linktitle: JsonTypeInfoResolverChain
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Metadata::JsonTypeInfoResolverChain class in C++.'
type: docs
weight: 1800
url: /cpp/system.text.json.serialization.metadata/jsontypeinforesolverchain/
---
## JsonTypeInfoResolverChain class




```cpp
class JsonTypeInfoResolverChain : public System::Text::Json::Serialization::ConfigurationList<System::SharedPtr<IJsonTypeInfoResolver>>,
                                  public System::Text::Json::Serialization::Metadata::IJsonTypeInfoResolver,
                                  public System::Text::Json::Serialization::Metadata::IBuiltInJsonTypeInfoResolver
```

## Methods

| Method | Description |
| --- | --- |
| [AddFlattened](./addflattened/)(System::SharedPtr\<IJsonTypeInfoResolver\>) |  |
| [get_IsReadOnly](./get_isreadonly/)() const override | Checks if collection is read only. |
| [GetTypeInfo](./gettypeinfo/)(const TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [JsonTypeInfoResolverChain](./jsontypeinforesolverchain/)() |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [ConfigurationList](../../system.text.json.serialization/configurationlist/)
* Class [IJsonTypeInfoResolver](../ijsontypeinforesolver/)
* Class [IBuiltInJsonTypeInfoResolver](../ibuiltinjsontypeinforesolver/)
* Namespace [System::Text::Json::Serialization::Metadata](../)
* Library [Aspose.PDF for C++](../../)
