---
title: System::Runtime::Serialization::SerializationInfo::SerializationInfo constructor
linktitle: SerializationInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::Serialization::SerializationInfo::SerializationInfo constructor. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.runtime.serialization/serializationinfo/serializationinfo/
---
## SerializationInfo::SerializationInfo constructor


RTTI information.

```cpp
System::Runtime::Serialization::SerializationInfo::SerializationInfo(const System::TypeInfo &type, const System::SharedPtr<IFormatterConverter> &converter)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const System::TypeInfo\& | The [System::TypeInfo](../../../system/typeinfo/) of the object to serialize. |
| converter | const System::SharedPtr\<IFormatterConverter\>\& | The [IFormatterConverter](../../iformatterconverter/) used during deserialization. |
## Remarks


Creates a new instance of the [SerializationInfo](../) class. 
## See Also

* Class [TypeInfo](../../../system/typeinfo/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatterConverter](../../iformatterconverter/)
* Class [SerializationInfo](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
