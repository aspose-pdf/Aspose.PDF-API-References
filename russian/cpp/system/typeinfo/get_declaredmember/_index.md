---
title: "Метод System::TypeInfo::get_DeclaredMember"
linktitle: "get_DeclaredMember"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::TypeInfo::get_DeclaredMember. Возвращает список членов с указанным именем в C++."
type: docs
weight: 1300
url: /ru/cpp/system/typeinfo/get_declaredmember/
---
## TypeInfo::get_DeclaredMember method


Получает список членов с указанным именем.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::get_DeclaredMember(const String &name) const
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
