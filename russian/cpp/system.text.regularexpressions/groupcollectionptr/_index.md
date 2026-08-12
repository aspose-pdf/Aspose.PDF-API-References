---
title: "System::Text::RegularExpressions::GroupCollectionPtr класс"
linktitle: "GroupCollectionPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::RegularExpressions::GroupCollectionPtr класс. Указатель на коллекцию групп. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по константной ссылке в C++."
type: docs
weight: 500
url: /ru/cpp/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr class


[Group](../group/) collection pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class GroupCollectionPtr : public System::SmartPtr<T0>
```

## Методы

| Метод | Описание |
| --- | --- |
| [GroupCollectionPtr](./groupcollectionptr/)() | Конструктор нулевого указателя. |
| [GroupCollectionPtr](./groupcollectionptr/)(const SharedPtr\<GroupCollection\>\&) | Конструктор преобразования типа. |
| [operator[]](./operator[]/)(size_t) const | [Group](../group/) аксессор. |
## См. также

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
