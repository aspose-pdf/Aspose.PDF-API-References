---
title: System::Reflection::MemberInfo::GetCustomAttributes method
linktitle: GetCustomAttributes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::MemberInfo::GetCustomAttributes method. Returns an array containing objects that represent all custom attributes applied to the type represented by the current object in C++.'
type: docs
weight: 700
url: /cpp/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(bool) const method


Returns an array containing objects that represent all custom attributes applied to the type represented by the current object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| inherit | bool | Whether to check inherited attributes, too. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const method


Returns an array containing objects that represent all custom attributes applied to the type represented by the current object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const TypeInfo\& | Type of attribute to look for. |
| inherit | bool | Whether to check inherited attributes, too. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
