---
title: System::Collections::IList class
linktitle: IList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IList class. IList Represents a non-generic collection of objects that can be individually accessed by index in C++.'
type: docs
weight: 1000
url: /cpp/system.collections/ilist/
---
## IList class


[IList](./) Represents a non-generic collection of objects that can be individually accessed by index.

```cpp
class IList : public virtual System::Collections::ICollection
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Add](./add/)(SharedPtr\<System::Object\>) | Adds item to the end of list. |
| virtual [Clear](./clear/)() | Removes all items from the list. |
| virtual [Contains](./contains/)(SharedPtr\<System::Object\>) const | Checks if the item is in the list. |
| virtual [get_IsFixedSize](./get_isfixedsize/)() const | Gets a value indicating whether the list has a fixed size. |
| virtual [idx_get](./idx_get/)(int, int) const | RTTI information. |
| virtual [IndexOf](./indexof/)(SharedPtr\<System::Object\>) const | Gets the first index of the specified item. |
| virtual [Insert](./insert/)(int, SharedPtr\<System::Object\>) | Inserts the item to the list at the specified index. |
| virtual [Remove](./remove/)(SharedPtr\<System::Object\>) | Removes the first instance of the specified item from the list. |
| virtual [RemoveAt](./removeat/)(int) | Removes the item from the list at the specified index. |
## See Also

* Class [ICollection](../icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
