---
title: System::Collections::Generic::HashSet class
linktitle: HashSet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::HashSet class. Forward declaration of HashSet class in C++.'
type: docs
weight: 1700
url: /cpp/system.collections.generic/hashset/
---
## HashSet class


Forward declaration of [HashSet](./) class.

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Methods

| Method | Description |
| --- | --- |
| [HashSet](./hashset/)() | RTTI information. |
| [HashSet](./hashset/)(int) | Creates empty set with specified capacity. |
| [HashSet](./hashset/)(const SharedPtr\<IEqualityComparer\<T\>\>\&) | Creates empty set that uses the specified equality comparer. |
| [HashSet](./hashset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Creates hashset based on enumerable values. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Base type. |
| [ThisPtr](./thisptr/) | Pointer type. |
| [ThisType](./thistype/) | Self type. |
## Remarks


Set implementation based on hashing. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## See Also

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
