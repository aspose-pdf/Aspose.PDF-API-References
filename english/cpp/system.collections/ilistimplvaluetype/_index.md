---
title: System::Collections::IListImplValueType class
linktitle: IListImplValueType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IListImplValueType class. Stub that implements System::Collections::IList interface on System::Collections::Generic::List object Implementation for value types in C++.'
type: docs
weight: 1200
url: /cpp/system.collections/ilistimplvaluetype/
---
## IListImplValueType class


Stub that implements [System::Collections::IList](../ilist/) interface on [System::Collections::Generic::List](../../system.collections.generic/list/) object Implementation for value types.

```cpp
template<typename T>class IListImplValueType : public virtual System::Collections::IList
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Adds element to the end of list. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Checks if item is present in list. |
| [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) methods implementation Gets number of elements in collection. |
| [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) implementation Returns an enumerator that iterates through a collection. |
| [idx_get](./idx_get/)(int, int) const override | Gets the element at the specified index. |
| [IListImplValueType](./ilistimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IList\<T\>\>) | Creates new object instance. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Gets index of first appearance of item in container. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Inserts element into specified position, shifting other elements. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Removes first instance of specific item from list. |
| [RemoveAt](./removeat/)(int) override | Removes item at specified position. |
## See Also

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
