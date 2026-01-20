---
title: System::Reflection::MemberInfo class
linktitle: MemberInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::MemberInfo class. Provides reflection information on members. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.reflection/memberinfo/
---
## MemberInfo class


Provides reflection information on members. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MemberInfo : public System::Object
```

## Nested classes

* Class [TypeInternal](./typeinternal/)
## Methods

| Method | Description |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Adds attribute to collection. |
| [get_DeclaringType](./get_declaringtype/)() const | Gets declaring type. |
| [get_FullName](./get_fullname/)() const | Gets member full name. Can be different in manually implemented parts. |
| virtual [get_MemberType](./get_membertype/)() const | Gets a [System::Reflection::MemberTypes](../membertypes/) value indicating the type of the member - method, constructor, event, and so on. |
| [get_Name](./get_name/)() const | Gets member name. |
| [get_ReflectedType](./get_reflectedtype/)() const | Gets reflected type type. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Returns an array containing objects that represent all custom attributes applied to the type represented by the current object. |
| [GetCustomAttributes](./getcustomattributes/)(bool) const | Returns an array containing objects that represent all custom attributes applied to the type represented by the current object. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ObjectPtr](./objectptr/) | Alias for a shared pointer to [Object](../../system/object/). |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
