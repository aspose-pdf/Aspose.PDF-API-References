---
title: System::Collections::IListImplRefType class
linktitle: IListImplRefType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IListImplRefType class. Stub that implements System::Collections::IList interface on System::Collections::Generic::List object Implementation for reference types in C++.'
type: docs
weight: 1100
url: /cpp/system.collections/ilistimplreftype/
---
## IListImplRefType class


Stub that implements [System::Collections::IList](../ilist/) interface on [System::Collections::Generic::List](../../system.collections.generic/list/) object Implementation for reference types.

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Adds element to the end of list. |
| static [BoxValue](./boxvalue/)(System::SharedPtr\<T\>) | Converting type reference into object value into object. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Checks if item is present in list. |
| [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) methods implementation Gets number of elements in collection. |
| [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) implementation Returns an enumerator that iterates through a collection. |
| [idx_get](./idx_get/)(int, int) const override | Gets the element at the specified index. |
| [IListImplRefType](./ilistimplreftype/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<T\>\>\>) | Creates new object instance. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Gets index of first appearance of item in container. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Inserts element into specified position, shifting other elements. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Removes first instance of specific item from list. |
| [RemoveAt](./removeat/)(int) override | Removes item at specified position. |
| static [UnboxValue](./unboxvalue/)(System::SharedPtr\<System::Object\>) | Converting object value into partucular type reference. |
## See Also

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
