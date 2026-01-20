---
title: System::Collections::Generic::ISet class
linktitle: ISet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ISet class. Interface of collection containing a set of unique elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.collections.generic/iset/
---
## ISet class


Interface of collection containing a set of unique elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| virtual [ExceptWith](./exceptwith/)(IEnumerablePtr) | Removes group of elements. |
| virtual [IntersectWith](./intersectwith/)(IEnumerablePtr) | Removes elements not present in different container. |
| virtual [IsProperSubsetOf](./ispropersubsetof/)(IEnumerablePtr) | Checks if current set is a strict subset of other container. |
| virtual [IsProperSupersetOf](./ispropersupersetof/)(IEnumerablePtr) | Checks if current set is a strict superset of other container. |
| virtual [IsSubsetOf](./issubsetof/)(IEnumerablePtr) | Checks if current set is a subset of other container. |
| virtual [IsSupersetOf](./issupersetof/)(IEnumerablePtr) | Checks if current set is a superset of other container. |
| virtual [Overlaps](./overlaps/)(IEnumerablePtr) | Checks if set overlaps with other container. |
| virtual [SetEquals](./setequals/)(IEnumerablePtr) | Checks if set and container contain same elements. |
| virtual [SymmetricExceptWith](./symmetricexceptwith/)(IEnumerablePtr) | Calculates symmetric exception of two containers. Removes all elements that are present in both containers, but at the same time adds all elements present in **other**, but not in current set. |
| virtual [UnionWith](./unionwith/)(IEnumerablePtr) | Adds elements from specified collection that are not present in current set yet. |
| virtual [~ISet](./~iset/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | RTTI information. |

## See Also

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
