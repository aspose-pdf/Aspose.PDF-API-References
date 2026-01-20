---
title: System::Collections::Generic::ICollection class
linktitle: ICollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ICollection class. Interface of collection of elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1900
url: /cpp/system.collections.generic/icollection/
---
## ICollection class


Interface of collection of elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Add](./add/)(const T\&) | Adds element into collection. |
| virtual [Clear](./clear/)() | Deletes all elements from collection. |
| virtual [Contains](./contains/)(const T\&) const | Checks if element is present in collection. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) | Copies all collection elements to existing array elements. |
| virtual [get_Count](./get_count/)() const | Gets number of elements in collection. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Checks if collection is read only. |
| [get_SyncRoot](./get_syncroot/)() const | Gets the object the collection is being synchronized through. |
| [ICollection](./icollection/)() | Default constructor. |
| [ICollection](./icollection/)(const ICollection\&) | Copy constructor. |
| [ICollection](./icollection/)(ICollection\&&) | Move constructor. |
| [operator=](./operator=/)(ICollection\&&) | Move assignment operator. |
| [operator=](./operator=/)(const ICollection\&) | Move assignment operator. |
| virtual [Remove](./remove/)(const T\&) | Deletes element from collection. |
| virtual [~ICollection](./~icollection/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) | Collection type name. |
| [ValueType](./valuetype/) | RTTI information. |

## See Also

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
