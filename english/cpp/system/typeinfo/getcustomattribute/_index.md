---
title: System::TypeInfo::GetCustomAttribute method
linktitle: GetCustomAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::TypeInfo::GetCustomAttribute method. Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object in C++.'
type: docs
weight: 3000
url: /cpp/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute method


Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const TypeInfo\& | The constant reference to the [TypeInfo](../) object representing the type of the attribute to search |

### ReturnValue

A pointer to an object representing the found attribute, or null-pointer if no attribute was foud matching the search criteria

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
