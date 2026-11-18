---
title: System::Text::Json::Nodes::JsonValuePrimitive class
linktitle: JsonValuePrimitive
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Nodes::JsonValuePrimitive class in C++.'
type: docs
weight: 1300
url: /cpp/system.text.json.nodes/jsonvalueprimitive/
---
## JsonValuePrimitive class




```cpp
template<typename TValue>class JsonValuePrimitive : public System::Text::Json::Nodes::JsonValue<TValue>
```

## Methods

| Method | Description |
| --- | --- |
| [DeepCloneCore](./deepclonecore/)() override |  |
| [DeepEqualsCore](./deepequalscore/)(System::SharedPtr\<JsonNode\>) override |  |
| [JsonValuePrimitive](./jsonvalueprimitive/)(TValue, System::SharedPtr\<Serialization::JsonConverter\<TValue\>\>, Nullable\<JsonNodeOptions\>) |  |
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
