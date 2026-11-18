---
title: System::Text::Json::Serialization::Converters::ArrayConverter class
linktitle: ArrayConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ArrayConverter class in C++.'
type: docs
weight: 100
url: /cpp/system.text.json.serialization.converters/arrayconverter/
---
## ArrayConverter class




```cpp
template<typename TCollection,typename TElement>class ArrayConverter : public System::Text::Json::Serialization::Converters::IEnumerableDefaultConverter<System::SharedPtr<Array<TElement>>, TElement>
```

## Methods

| Method | Description |
| --- | --- |
| [get_CanHaveMetadata](./get_canhavemetadata/)() override |  |
| [get_IsConvertibleCollection](./get_isconvertiblecollection/)() override |  |
| [get_SupportsCreateObjectDelegate](./get_supportscreateobjectdelegate/)() override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [IEnumerableDefaultConverter](../ienumerabledefaultconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
