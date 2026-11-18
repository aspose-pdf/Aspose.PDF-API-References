---
title: System::Text::Json::Nodes::JsonArray class
linktitle: JsonArray
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Nodes::JsonArray class in C++.'
type: docs
weight: 100
url: /cpp/system.text.json.nodes/jsonarray/
---
## JsonArray class




```cpp
class JsonArray : public System::Text::Json::Nodes::JsonNode,
                  public System::Collections::Generic::IList<System::SharedPtr<JsonNode>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<JsonNode\>\&) override |  |
| [Clear](./clear/)() override | Deletes all elements from collection. |
| [Contains](./contains/)(const System::SharedPtr\<JsonNode\>\&) const override |  |
| static [Create](./create/)(JsonElement, Nullable\<JsonNodeOptions\>) |  |
| [get_Count](./get_count/)() const override | Gets number of elements in collection. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [GetValues](./getvalues/)() |  |
| [idx_get](./idx_get/)(int) const override | Gets element at specified index. |
| [idx_set](./idx_set/)(int, System::SharedPtr\<JsonNode\>) override |  |
| [IndexOf](./indexof/)(const System::SharedPtr\<JsonNode\>\&) const override |  |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<JsonNode\>\&) override |  |
| [JsonArray](./jsonarray/)(Nullable\<JsonNodeOptions\>) |  |
| [JsonArray](./jsonarray/)(JsonNodeOptions, const System::SharedPtr\<Array\<System::SharedPtr\<JsonNode\>\>\>\&) |  |
| [JsonArray](./jsonarray/)(const System::SharedPtr\<Array\<System::SharedPtr\<JsonNode\>\>\>\&) |  |
| [Remove](./remove/)(const System::SharedPtr\<JsonNode\>\&) override |  |
| [RemoveAll](./removeall/)(Func\<System::SharedPtr\<JsonNode\>, bool\>) |  |
| [RemoveAt](./removeat/)(int32_t) override |  |
| [RemoveRange](./removerange/)(int32_t, int32_t) |  |
| [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonNode](../jsonnode/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Text::Json::Nodes](../)
* Library [Aspose.PDF for C++](../../)
