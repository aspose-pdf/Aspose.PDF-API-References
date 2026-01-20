---
title: System::Collections::Generic::List class
linktitle: List
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::List class. List forward declaration in C++.'
type: docs
weight: 3300
url: /cpp/system.collections.generic/list/
---
## List class


[List](./) forward declaration.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ specific. |
| [Add](./add/)(const T\&) override | Adds element to the end of list. |
| [AddInitializer](./addinitializer/)(int, const T *) | Adds elements to list; used when translating initializers. |
| [AddRange](./addrange/)(IEnumerablePtr) | Adds all elements from collection (or itself) to the end of current list. |
| [AsReadOnly](./asreadonly/)() | Gets read-only reference to this collection. |
| [begin](./begin/)() | Gets iterator to the first element of collection. |
| [begin](./begin/)() const | Gets iterator to the first element of the const-qualified collection. |
| [BinarySearch](./binarysearch/)(const T\&) const | Looks for item in a sorted list. |
| [BinarySearch](./binarysearch/)(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Looks for item in a sorted list. |
| [BinarySearch](./binarysearch/)(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Looks for item in a sorted list. |
| [cbegin](./cbegin/)() const | Gets iterator to the first const-qualified element of collection. |
| [cend](./cend/)() const | Gets iterator for a non-existent const-qualified element behind the end of the collection. |
| [Clear](./clear/)() override | Deletes all elements. |
| [Contains](./contains/)(const T\&) const override | Checks if item is present in list. |
| [ConvertAll](./convertall/)(Converter\<T, OutputType\>) | Creates a list of elements converted to different type. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Copies list elements into existing array elements. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<T\>\&) | Copies all elements into existing array elements. |
| [CopyTo](./copyto/)(int, const System::ArrayPtr\<T\>\&, int, int) | Copies elements starting from the specified index into existing array elements. |
| [crbegin](./crbegin/)() const | Gets a reverse iterator to the last const-qualified element of collection (first in reverse). |
| [crend](./crend/)() const | Gets a reverse iterator for a non-existent const-qualified element before the start of the collection. |
| [data](./data/)() | Underlying data structure access function. |
| [data](./data/)() const | Underlying data structure access function. |
| [end](./end/)() | Gets iterator for a non-existent element behind the end of the collection. |
| [end](./end/)() const | Gets iterator for a non-existent element behind the end of the const-qualified collection. |
| [Exists](./exists/)(System::Predicate\<T\>) | Checks if element adhering to specific predicate exists in list. |
| [Find](./find/)(System::Predicate\<T\>) | Looks for element adhering to specific predicate. |
| [FindAll](./findall/)(System::Predicate\<T\>) | Looks for elements adhering to specific predicate. |
| [FindIndex](./findindex/)(System::Predicate\<T\>) | Looks for element adhering to specific predicate. |
| [FindIndex](./findindex/)(int, System::Predicate\<T\>) | Looks for element adhering to specific predicate. |
| [FindIndex](./findindex/)(int, int, System::Predicate\<T\>) | Looks for element adhering to specific predicate. |
| [FindLast](./findlast/)(System::Predicate\<T\>) | Looks for last element adhering to specific predicate. |
| [ForEach](./foreach/)(System::Action\<T\>) | Applies action to all elements in list. |
| [get_Capacity](./get_capacity/)() const | Gets current list capacity. |
| [get_Count](./get_count/)() const override | Gets number of elements in current list. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through list elements. |
| [GetRange](./getrange/)(int, int) | Creates slice of list. |
| [idx_get](./idx_get/)(int) const override | Gets element at specific position. |
| [idx_set](./idx_set/)(int, T) override | Sets element at specific position. |
| [IndexOf](./indexof/)(const T\&) const override | Gets first index of specific item. |
| [IndexOf](./indexof/)(const T\&, int) const | Looks for specific item in list. |
| [Insert](./insert/)(int, const T\&) override | Inserts item at specified position. |
| [InsertRange](./insertrange/)(int, IEnumerablePtr) | Inserts data range at specific position. |
| [LastIndexOf](./lastindexof/)(const T\&) const | Searches for the specified object and returns the zero-based index of the last occurrence within the entire list. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t) const | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](./) that extends from the first element to the specified index. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t, int32_t) const | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the [List](./) that contains the specified number of elements and ends at the specified index. |
| [List](./list/)() | Creates empty list. |
| [List](./list/)(int) | Creates list with pre-defined capacity. |
| [List](./list/)(IEnumerablePtr) | Copy constructor. |
| [operator[]](./operator[]/)(int) | Accessor function. |
| [operator[]](./operator[]/)(int) const | Accessor function. |
| [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| [Remove](./remove/)(const T\&) override | Removes first instance of specific item from list. |
| [RemoveAll](./removeall/)(Predicate\<T\>) | Removes all elements matching specific predicate. |
| [RemoveAt](./removeat/)(int) override | Removes item at specified position. |
| [RemoveRange](./removerange/)(int, int) | Removes slice of list. |
| [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| [Reverse](./reverse/)() | Reverses elements order of the whole list. |
| [Reverse](./reverse/)(int, int) | Reverses elements order of the list slice. |
| [set_Capacity](./set_capacity/)(int) | Sets list capacity. |
| [Sort](./sort/)(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Sorts elements in the list. |
| [Sort](./sort/)() | Sorts elements in the list using default comparator. |
| [Sort](./sort/)(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) | Sorts elements in the list slice. |
| [Sort](./sort/)(Comparison\<T\>, bool) | Sorts elements in the list. |
| [ToArray](./toarray/)() const | Converst list to array. |
| [TrimExcess](./trimexcess/)() | Makes list capacity to fit its size. |
| [TrueForAll](./trueforall/)(System::Predicate\<T\>) | Determines whether every element in the collection matches the conditions defined by the specified predicate. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) | Interface type. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [IEnumerablePtr](./ienumerableptr/) | Container holding elements of same type we hold. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) type. |
| [iterator](./iterator/) | Iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [ValueType](./valuetype/) | This type. |
| [vector_t](./vector_t/) | RTTI information. |
## Remarks


[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Create the first list.
  auto list1 = MakeObject<List<int>>();

  // Fill the first list.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Sort the first list.
  // The first list items will be: {-5, 1, 3, 8}
  list1->Sort();

  // Remove the item at index 2.
  // The first list items will be: {-5, 1, 8}
  list1->RemoveAt(2);

  // Insert the item to index 1.
  // The first list items will be: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Create the second list.
  auto list2 = MakeObject<List<int>>();

  // Fill the second list.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Append elements from the second list to the first one.
  list1->AddRange(list2);

  // Print the first list items.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
-5 15 1 8 10 20 30
*/
```

## See Also

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
