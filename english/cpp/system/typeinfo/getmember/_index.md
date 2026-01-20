---
title: System::TypeInfo::GetMember method
linktitle: GetMember
second_title: Aspose.PDF for C++ API Reference
description: 'System::TypeInfo::GetMember method. Gets list of the members with specified name in C++.'
type: docs
weight: 3800
url: /cpp/system/typeinfo/getmember/
---
## TypeInfo::GetMember method


Gets list of the members with specified name.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | Name of the member to get. |

### ReturnValue

[Array](../../array/) of member descriptors (empty if no member is found).

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [MemberInfo](../../../system.reflection/memberinfo/)
* Class [String](../../string/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
