---
title: System::Text::Json::Nodes::JsonValueCustomized class
linktitle: JsonValueCustomized
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Nodes::JsonValueCustomized class in C++.'
type: docs
weight: 700
url: /cpp/system.text.json.nodes/jsonvaluecustomized/
---
## JsonValueCustomized class




```cpp
template<typename TValue>class JsonValueCustomized : public System::Text::Json::Nodes::JsonValue<TValue>
```

## Methods

| Method | Description |
| --- | --- |
| [DeepCloneCore](./deepclonecore/)() override |  |
| [JsonValueCustomized](./jsonvaluecustomized/)(TValue, System::SharedPtr\<Serialization::Metadata::JsonTypeInfo\<TValue\>\>, Nullable\<JsonNodeOptions\>) |  |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## Fields

| Field | Description |
| --- | --- |
| [Value](../jsonvalue/value/) |  |
## See Also

* Class [JsonValue](../jsonvalue/)
* Namespace [System::Text::Json::Nodes](../)
* Library [Aspose.PDF for C++](../../)
