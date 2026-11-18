---
title: System::Text::Json::Nodes::JsonObject class
linktitle: JsonObject
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::Nodes::JsonObject class in C++.'
type: docs
weight: 400
url: /cpp/system.text.json.nodes/jsonobject/
---
## JsonObject class




```cpp
class JsonObject : public System::Text::Json::Nodes::JsonNode,
                   public System::Collections::Generic::IDictionary<String, System::SharedPtr<JsonNode>>,
                   public System::Collections::Generic::IList<Collections::Generic::KeyValuePair<String, System::SharedPtr<JsonNode>>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const String\&, const System::SharedPtr\<JsonNode\>\&) override |  |
| [Add](./add/)(const Collections::Generic::KeyValuePair\<String, System::SharedPtr\<JsonNode\>\>\&) override |  |
| [Clear](./clear/)() override | Deletes all elements from collection. |
| [ContainsKey](./containskey/)(const String\&) const override | Checks if container contains key. |
| static [Create](./create/)(JsonElement, Nullable\<JsonNodeOptions\>) |  |
| [get_Count](./get_count/)() const override | Unhides get_Count member function. |
| [GetAt](./getat/)(int32_t) |  |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [idx_get](./idx_get/)(const String\&) const override | Getter function. |
| [idx_get](./idx_get/)(int32_t) const override |  |
| [idx_set](./idx_set/)(const String\&, System::SharedPtr\<JsonNode\>) override |  |
| [idx_set](./idx_set/)(int32_t, Collections::Generic::KeyValuePair\<String, System::SharedPtr\<JsonNode\>\>) override |  |
| [IndexOf](./indexof/)(const String\&) const |  |
| [Insert](./insert/)(int32_t, String, System::SharedPtr\<JsonNode\>) |  |
| [JsonObject](./jsonobject/)(Nullable\<JsonNodeOptions\>) |  |
| [JsonObject](./jsonobject/)(System::SharedPtr\<Collections::Generic::IEnumerable\<Collections::Generic::KeyValuePair\<String, System::SharedPtr\<JsonNode\>\>\>\>, Nullable\<JsonNodeOptions\>) |  |
| [Remove](./remove/)(const String\&) override | Removes key from container. |
| [RemoveAt](./removeat/)(int32_t) override |  |
| [SetAt](./setat/)(int32_t, String, System::SharedPtr\<JsonNode\>) |  |
| [SetAt](./setat/)(int32_t, System::SharedPtr\<JsonNode\>) |  |
| [TryAdd](./tryadd/)(String, System::SharedPtr\<JsonNode\>) |  |
| [TryAdd](./tryadd/)(String, System::SharedPtr\<JsonNode\>, int32_t\&) |  |
| [TryGetPropertyValue](./trygetpropertyvalue/)(String, System::SharedPtr\<JsonNode\>\&) |  |
| [TryGetPropertyValue](./trygetpropertyvalue/)(String, System::SharedPtr\<JsonNode\>\&, int32_t\&) |  |
| [WriteTo](./writeto/)(System::SharedPtr\<Utf8JsonWriter\>, System::SharedPtr\<JsonSerializerOptions\>) override |  |
## See Also

* Class [JsonNode](../jsonnode/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Text::Json::Nodes](../)
* Library [Aspose.PDF for C++](../../)
