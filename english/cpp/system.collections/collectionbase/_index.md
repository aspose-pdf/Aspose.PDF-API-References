---
title: System::Collections::CollectionBase class
linktitle: CollectionBase
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::CollectionBase class. Provides an abstract base class for a strongly typed collection in C++.'
type: docs
weight: 300
url: /cpp/system.collections/collectionbase/
---
## CollectionBase class


Provides an abstract base class for a strongly typed collection.

```cpp
template<typename T>class CollectionBase : public virtual System::Collections::Generic::IEnumerable<T>
```


| Parameter | Description |
| --- | --- |
| T | Type of elements of the collection |
## Nested classes

* Class [ListImpl](./listimpl/)
## Methods

| Method | Description |
| --- | --- |
| [Clear](./clear/)() | Removes all objects from the collection instance. This method cannot be overridden. |
| [get_Capacity](./get_capacity/)() | Returns the number of elements that the collection can contain. |
| [get_Count](./get_count/)() | Returns the number of elements contained in the collection instance. This method cannot be overridden. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator that iterates through the collection instance. |
| [RemoveAt](./removeat/)(int32_t) | Removes the element at the specified index of the collection instance. This method is not overridable. |
| [set_Capacity](./set_capacity/)(int32_t) | Sets the number of elements that the collection can contain. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
