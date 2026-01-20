---
title: System::Collections::Generic::SortedSet class
linktitle: SortedSet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::SortedSet class. Forward declaration of SortedSet class in C++.'
type: docs
weight: 4400
url: /cpp/system.collections.generic/sortedset/
---
## SortedSet class


Forward declaration of [SortedSet](./) class.

```cpp
template<typename T>class SortedSet : public System::Collections::Generic::BaseSet<T, std::set<T, ComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Methods

| Method | Description |
| --- | --- |
| [get_Max](./get_max/)() const | Gets the maximum value in the [SortedSet](./). |
| [SortedSet](./sortedset/)() | RTTI information. |
| [SortedSet](./sortedset/)(int) | Creates empty set with specified capacity. |
| [SortedSet](./sortedset/)(const SharedPtr\<IComparer\<T\>\>\&) | Creates empty set that uses the specified equality comparer. |
| [SortedSet](./sortedset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Creates [SortedSet](./) based on enumerable values. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Vase type. |
| [ThisPtr](./thisptr/) | Pointer type. |
| [ThisType](./thistype/) | Self type. |
## Remarks


Implementation a set of ordered objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## See Also

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
