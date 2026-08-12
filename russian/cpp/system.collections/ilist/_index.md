---
title: "System::Collections::IList класс"
linktitle: "IList"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::IList класс. IList представляет собой необобщённую коллекцию объектов, к которым можно обращаться по отдельности по индексу в C++."
type: docs
weight: 1000
url: /ru/cpp/system.collections/ilist/
---
## IList class


[IList](./) Represents a non-generic collection of objects that can be individually accessed by index.

```cpp
class IList : public virtual System::Collections::ICollection
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Add](./add/)(SharedPtr\<System::Object\>) | Добавляет элемент в конец списка. |
| virtual [Clear](./clear/)() | Удаляет все элементы из списка. |
| virtual [Contains](./contains/)(SharedPtr\<System::Object\>) const | Проверяет, находится ли элемент в списке. |
| virtual [get_IsFixedSize](./get_isfixedsize/)() const | Возвращает значение, указывающее, имеет ли список фиксированный размер. |
| virtual [idx_get](./idx_get/)(int, int) const | Информация RTTI. |
| virtual [IndexOf](./indexof/)(SharedPtr\<System::Object\>) const | Возвращает первый индекс указанного элемента. |
| virtual [Insert](./insert/)(int, SharedPtr\<System::Object\>) | Вставляет элемент в список по указанному индексу. |
| virtual [Remove](./remove/)(SharedPtr\<System::Object\>) | Удаляет первое вхождение указанного элемента из списка. |
| virtual [RemoveAt](./removeat/)(int) | Удаляет элемент из списка по указанному индексу. |
## См. также

* Class [ICollection](../icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
