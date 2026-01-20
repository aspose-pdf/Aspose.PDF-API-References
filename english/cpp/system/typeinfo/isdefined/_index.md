---
title: System::TypeInfo::IsDefined method
linktitle: IsDefined
second_title: Aspose.PDF for C++ API Reference
description: 'System::TypeInfo::IsDefined method. NOT IMPLEMENTED. Indicates whether one or more attributes of the specified type or of its derived types is applied to this member in C++.'
type: docs
weight: 4400
url: /cpp/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined method


NOT IMPLEMENTED. Indicates whether one or more attributes of the specified type or of its derived types is applied to this member.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const TypeInfo\& | The type of custom attribute to search for. The search includes derived types. |
| inherit | bool | true to search this member's inheritance chain to find the attributes; otherwise, false. This parameter is ignored for properties and events. |

### ReturnValue

true if one or more instances of attributeType or any of its derived types is applied to this member; otherwise, false.

## See Also

* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
