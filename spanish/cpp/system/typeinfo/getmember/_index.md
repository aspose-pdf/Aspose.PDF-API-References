---
title: "Método System::TypeInfo::GetMember"
linktitle: "GetMember"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::TypeInfo::GetMember. Obtiene una lista de los miembros con el nombre especificado en C++."
type: docs
weight: 3800
url: /es/cpp/system/typeinfo/getmember/
---
## TypeInfo::GetMember method


Obtiene la lista de los miembros con el nombre especificado.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const String\& | Nombre del miembro a obtener. |

### ReturnValue

[Array](../../array/) of member descriptors (empty if no member is found).

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [MemberInfo](../../../system.reflection/memberinfo/)
* Class [String](../../string/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
