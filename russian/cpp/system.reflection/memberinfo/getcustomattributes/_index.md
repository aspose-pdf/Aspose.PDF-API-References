---
title: "System::Reflection::MemberInfo::GetCustomAttributes method"
linktitle: "GetCustomAttributes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Reflection::MemberInfo::GetCustomAttributes method. Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представленному текущим объектом, в C++."
type: docs
weight: 700
url: /ru/cpp/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(bool) const method


Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inherit | bool | Нужно ли также проверять унаследованные атрибуты. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const method


Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeType | const TypeInfo\& | Тип атрибута для поиска. |
| inherit | bool | Нужно ли также проверять унаследованные атрибуты. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
