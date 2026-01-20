---
title: System::Collections::Generic::BaseSet class
linktitle: BaseSet
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Collections::Generic::BaseSet class in C++.'
type: docs
weight: 800
url: /cpp/system.collections.generic/baseset/
---
## BaseSet class




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ specific. |
| [Add](./add/)(const T\&) override | Adds element into set. |
| [begin](./begin/)() const | Gets iterator to the first element of the const-qualified collection. |
| [cbegin](./cbegin/)() const | Gets iterator to the first const-qualified element of collection. |
| [cend](./cend/)() const | Gets iterator for a non-existent const-qualified element behind the end of the collection. |
| [Clear](./clear/)() override | Deletes all elements in set. |
| [Contains](./contains/)(const T\&) const override | Checks if element is present in set. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copies hash contents into existing array elements. |
| [data](./data/)() | Underlying data structure accessor. |
| [data](./data/)() const | Underlying data structure accessor. |
| [end](./end/)() const | Gets iterator for a non-existent element behind the end of the const-qualified collection. |
| [get_Count](./get_count/)() const override | Gets number of elements in set. |
| [GetEnumerator](./getenumerator/)() override | Creates enumerator. |
| [Remove](./remove/)(const T\&) override | Removes element from set. |
| [TryAdd](./tryadd/)(const T\&) | Adds element into set. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Implemented interface. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [IEnumerablePtr](./ienumerableptr/) | Enumerable interface pointer. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) pointer. |
| [iterator](./iterator/) | Iterator type. |
| [set_t](./set_t/) | Underlying data type. |
| [ThisPtr](./thisptr/) | Pointer type. |
| [ThisType](./thistype/) | Self type. |
| [ValueType](./valuetype/) | Value type. |
## See Also

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
