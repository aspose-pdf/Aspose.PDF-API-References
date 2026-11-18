---
title: System::Text::Json::Serialization::Metadata::JsonTypeInfoResolver::Combine method
linktitle: Combine
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Json::Serialization::Metadata::JsonTypeInfoResolver::Combine method. Returns an empty combined resolver in C++.'
type: docs
weight: 100
url: /cpp/system.text.json.serialization.metadata/jsontypeinforesolver/combine/
---
## JsonTypeInfoResolver::Combine() method


Returns an empty combined resolver.

```cpp
static System::SharedPtr<IJsonTypeInfoResolver> System::Text::Json::Serialization::Metadata::JsonTypeInfoResolver::Combine()
```


### ReturnValue

A resolver that always returns no metadata.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IJsonTypeInfoResolver](../../ijsontypeinforesolver/)
* Class [JsonTypeInfoResolver](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
## JsonTypeInfoResolver::Combine(const System::ArrayPtr\<System::SharedPtr\<IJsonTypeInfoResolver\>\>\&) method


Combines the specified resolvers into a single one.

```cpp
static System::SharedPtr<IJsonTypeInfoResolver> System::Text::Json::Serialization::Metadata::JsonTypeInfoResolver::Combine(const System::ArrayPtr<System::SharedPtr<IJsonTypeInfoResolver>> &resolvers)
```


| Parameter | Type | Description |
| --- | --- | --- |
| resolvers | const System::ArrayPtr\<System::SharedPtr\<IJsonTypeInfoResolver\>\>\& | The resolvers to combine. |

### ReturnValue

A resolver that queries the specified resolvers in order.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IJsonTypeInfoResolver](../../ijsontypeinforesolver/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [JsonTypeInfoResolver](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
