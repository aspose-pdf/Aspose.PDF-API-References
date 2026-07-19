---
title: "Метод System::TypeInfo::GetMember"
linktitle: "GetMember"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::TypeInfo::GetMember. Получает список членов с указанным именем в C++."
type: docs
weight: 3800
url: /ru/cpp/system/typeinfo/getmember/
---
## TypeInfo::GetMember method


Получает список членов с указанным именем.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const String\& | Имя получаемого члена. |

### ReturnValue

[Array](../../array/) of member descriptors (empty if no member is found).

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [MemberInfo](../../../system.reflection/memberinfo/)
* Class [String](../../string/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
