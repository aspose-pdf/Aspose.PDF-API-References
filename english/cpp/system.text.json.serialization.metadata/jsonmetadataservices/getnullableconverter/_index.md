---
title: System::Text::Json::Serialization::Metadata::JsonMetadataServices::GetNullableConverter method
linktitle: GetNullableConverter
second_title: Aspose.PDF for C++ API Reference
description: 'How to use GetNullableConverter method of System::Text::Json::Serialization::Metadata::JsonMetadataServices class in C++.'
type: docs
weight: 4500
url: /cpp/system.text.json.serialization.metadata/jsonmetadataservices/getnullableconverter/
---
## JsonMetadataServices::GetNullableConverter(System::SharedPtr\<JsonSerializerOptions\>) method




```cpp
template<typename T> static std::enable_if<System::Constraints::IsCsPointer<T>::value, System::SharedPtr<JsonConverter<Nullable<T>>>>::type System::Text::Json::Serialization::Metadata::JsonMetadataServices::GetNullableConverter(System::SharedPtr<JsonSerializerOptions> options)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [JsonConverter](../../../system.text.json.serialization/jsonconverter/)
* Class [Nullable](../../../system/nullable/)
* Class [JsonSerializerOptions](../../../system.text.json/jsonserializeroptions/)
* Class [JsonMetadataServices](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
## JsonMetadataServices::GetNullableConverter(System::SharedPtr\<JsonSerializerOptions\>) method




```cpp
template<typename T> static std::enable_if<!System::Constraints::IsCsPointer<T>::value, System::SharedPtr<JsonConverter<Nullable<T>>>>::type System::Text::Json::Serialization::Metadata::JsonMetadataServices::GetNullableConverter(System::SharedPtr<JsonSerializerOptions> options)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [JsonConverter](../../../system.text.json.serialization/jsonconverter/)
* Class [Nullable](../../../system/nullable/)
* Class [JsonSerializerOptions](../../../system.text.json/jsonserializeroptions/)
* Class [JsonMetadataServices](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
## JsonMetadataServices::GetNullableConverter(System::SharedPtr\<JsonTypeInfo\<T\>\>) method




```cpp
template<typename T> static std::enable_if<System::Constraints::IsCsPointer<T>::value, System::SharedPtr<JsonConverter<Nullable<T>>>>::type System::Text::Json::Serialization::Metadata::JsonMetadataServices::GetNullableConverter(System::SharedPtr<JsonTypeInfo<T>> underlyingTypeInfo)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [JsonConverter](../../../system.text.json.serialization/jsonconverter/)
* Class [Nullable](../../../system/nullable/)
* Class [JsonTypeInfo](../../jsontypeinfo/)
* Class [JsonMetadataServices](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
## JsonMetadataServices::GetNullableConverter(System::SharedPtr\<JsonTypeInfo\<T\>\>) method




```cpp
template<typename T> static std::enable_if<!System::Constraints::IsCsPointer<T>::value, System::SharedPtr<JsonConverter<Nullable<T>>>>::type System::Text::Json::Serialization::Metadata::JsonMetadataServices::GetNullableConverter(System::SharedPtr<JsonTypeInfo<T>> underlyingTypeInfo)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [JsonConverter](../../../system.text.json.serialization/jsonconverter/)
* Class [Nullable](../../../system/nullable/)
* Class [JsonTypeInfo](../../jsontypeinfo/)
* Class [JsonMetadataServices](../)
* Namespace [System::Text::Json::Serialization::Metadata](../../)
* Library [Aspose.PDF for C++](../../../)
