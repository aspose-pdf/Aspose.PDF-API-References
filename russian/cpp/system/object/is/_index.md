---
title: "System::Object::Is method"
linktitle: "Is"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Object::Is method. Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# ''is'' в C++."
type: docs
weight: 800
url: /ru/cpp/system/object/is/
---
## Object::Is method


Проверьте, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'.

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| targetType | const TypeInfo\& | Структура [TypeInfo](../../typeinfo/) описывающая тип, против которого проверяется текущий объект. |

### ReturnValue

Истина, если объект имеет помеченный тип или его подкласс, иначе ложь.

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
