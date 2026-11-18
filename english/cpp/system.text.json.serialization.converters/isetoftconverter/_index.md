---
title: System::Text::Json::Serialization::Converters::ISetOfTConverter class
linktitle: ISetOfTConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ISetOfTConverter class in C++.'
type: docs
weight: 2700
url: /cpp/system.text.json.serialization.converters/isetoftconverter/
---
## ISetOfTConverter class




```cpp
template<typename TCollection,typename TElement>class ISetOfTConverter : public System::Text::Json::Serialization::Converters::IEnumerableDefaultConverter<TCollection, TElement>
```

## Methods

| Method | Description |
| --- | --- |
| [ConfigureJsonTypeInfo](./configurejsontypeinfo/)(System::SharedPtr\<Metadata::JsonTypeInfoBase\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
| [get_CanPopulate](./get_canpopulate/)() override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [IEnumerableDefaultConverter](../ienumerabledefaultconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
