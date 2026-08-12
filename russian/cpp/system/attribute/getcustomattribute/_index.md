---
title: "System::Attribute::GetCustomAttribute method"
linktitle: "GetCustomAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Attribute::GetCustomAttribute method. Возвращает пользовательский атрибут указанного типа, применённый к указанному типу в C++."
type: docs
weight: 100
url: /ru/cpp/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute method


Возвращает пользовательский атрибут указанного типа, применённый к указанному типу.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | const TypeInfo\& | Атрибут типа, который получен |
| attributeType | const TypeInfo\& | Тип атрибута для получения |

### ReturnValue

Полученный атрибут или null, если указанный тип не имеет атрибута указанного типа.

## См. также

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
