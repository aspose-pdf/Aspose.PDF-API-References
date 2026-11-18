---
title: System::Text::Json::Serialization::Converters::ObjectWithParameterizedConstructorConverter class
linktitle: ObjectWithParameterizedConstructorConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Serialization::Converters::ObjectWithParameterizedConstructorConverter class in C++.'
type: docs
weight: 4200
url: /cpp/system.text.json.serialization.converters/objectwithparameterizedconstructorconverter/
---
## ObjectWithParameterizedConstructorConverter class




```cpp
template<typename T>class ObjectWithParameterizedConstructorConverter : public System::Text::Json::Serialization::Converters::ObjectDefaultConverter<T>
```

## Methods

| Method | Description |
| --- | --- |
| [get_ConstructorIsParameterized](./get_constructorisparameterized/)() override |  |
| [OnTryRead](./ontryread/)(Utf8JsonReader\&, const System::TypeInfo\&, System::SharedPtr\<JsonSerializerOptions\>, ReadStack\&, T\&) override |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## See Also

* Class [ObjectDefaultConverter](../objectdefaultconverter/)
* Namespace [System::Text::Json::Serialization::Converters](../)
* Library [Aspose.PDF for C++](../../)
