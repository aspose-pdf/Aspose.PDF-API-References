---
title: System::Array class
linktitle: Array
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array class. Class that represents an array data structure. Objects of this class should only be allocated using System::MakeArray() and System::MakeObject() functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system/array/
---
## Array class


Class that represents an array data structure. Objects of this class should only be allocated using [System::MakeArray()](../makearray/) and [System::MakeObject()](../makeobject/) functions. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class Array : public virtual System::Object,
                                  public System::Collections::Generic::IList<T>
```


| Parameter | Description |
| --- | --- |
| T | Type of elements of an array |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Not supported because the array represented by the current object is read-only. |
| [Array](./array/)() | Constructs an empty array. |
| [Array](./array/)(int, const T\&) | Filling constructor. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) | Filling constructor. |
| [Array](./array/)(int, const T) | Filling constructor. |
| [Array](./array/)(vector_t\&&) | Move constructor. |
| [Array](./array/)(const vector_t\&) | Copy constructor. |
| [Array](./array/)(const std::vector\<Q\>\&) | Constructs an [Array](./) object and fills it with values copied from an std::vector object whose values' type is the same as **T** but different from **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Constructs an [Array](./) object and fills it with values moved from an std::vector object whose values' type is the same as **T** but different from **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<UnderlyingType\>) | Constructs an [Array](./) object and fills it with values from the specified initializer list containing elements of **[UnderlyingType](./underlyingtype/)** type. |
| [Array](./array/)(const std::array\<UnderlyingType, InitArraySize\>\&) | Constructs an [Array](./) object and fills it with values from the specified array containing elements of **[UnderlyingType](./underlyingtype/)** type. |
| [Array](./array/)(std::initializer_list\<bool\>, int) | Constructs an [Array](./) object and fills it with values from the specified initializer list containing elements of bool type. |
| [begin](./begin/)() | Returns an iterator to the first element of the container. If the container is empty, the returned iterator will be equal to [end()](./end/). |
| [begin](./begin/)() const | Returns an iterator to the first element of the const-qualified container. If the container is empty, the returned iterator will be equal to [end()](./end/). |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const T\&) | Performs binary search in the sorted array. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) | NOT IMPLEMENTED. |
| [cbegin](./cbegin/)() const | Returns an iterator to the first const-qualified element of the container. If the container is empty, the returned iterator will be equal to [cend()](./cend/). |
| [cend](./cend/)() const | Returns an iterator to the element following the last element of the container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [Clear](./clear/)() override | Not supported because the array represented by the current object is read-only. |
| static [Clear](./clear/)(const ArrayPtr\<Type\>\&, int, int) | Replaces **count** values starting at the **startIndex** index in the specified array with default values. |
| [Clone](./clone/)() | Clones the array. |
| static [ConstrainedCopy](./constrainedcopy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copies a range of elements from an [System.Array](./) starting at the specified source. |
| [Contains](./contains/)(const T\&) const override | Determines if the specified item is in the array. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) | Constructs a new [Array](./) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter delegate. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) | Constructs a new [Array](./) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter function object. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Copies the specified number of elements from the source array to the destination array. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) | Copies the specified number of elements from the source array view to the destination array. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) | Copies the specified number of elements from the source array to the destination array view. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) | Copies the specified number of elements from the source array view to the destination array view. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Copies the specified number of elements from the source array on stack to the destination array. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) | Copies the specified number of elements from the source array to the destination array on stack. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) | Copies the specified number of elements from the source array on stack to the destination array on stack. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array view. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array view. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array on stack starting at the specified index to the specified position in destination array. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array starting at the specified index to the specified position in destination array on stack. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array on stack starting at the specified index to the specified position in destination array on stack. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Copies a specified number of elements from the source array view starting at the specified index to the specified position in destination array on stack. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copies all elements of the current array to the specified destination array. Elements are inserted into destination array starting at index specified by arrayIndex argument. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t) const | Copies all elements of the current array to the specified destination array. Elements are inserted into the destination array starting at index specified by dstIndex argument. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t) const | Copies all elements of the current array to the specified destination array view. Elements are inserted into the destination array view starting at index specified by dstIndex argument. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const | Copies a specified number of elements from the current array starting at specified position to specified destination array. Elements are inserted into the destination array starting at index specified by dstIndex argument. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const | Copies a specified number of elements from the current array starting at specified position to specified destination array view. Elements are inserted into the destination array view starting at index specified by dstIndex argument. |
| [Count](./count/)() const | Returns a number that represents the total number of all elements in all dimensions of the array. |
| [crbegin](./crbegin/)() const | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [crend()](./crend/). |
| [crend](./crend/)() const | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| [data](./data/)() | Returns a reference to the internal data structure used to store the array elements. |
| [data](./data/)() const | Returns a constant reference to the internal data structure used to store the array elements. |
| [data_ptr](./data_ptr/)() | Returns a raw pointer to the beginning of the memory buffer where the array elements are stored. |
| [data_ptr](./data_ptr/)() const | Returns a constant raw pointer to the beginning of the memory buffer where the array elements are stored. |
| [end](./end/)() | Returns an iterator to the element following the last element of the container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| [end](./end/)() const | Returns an iterator to the element following the last element of the const-qualified container. This element acts as a placeholder; attempting to access it results in undefined behavior. |
| static [Exists](./exists/)(ArrayPtr\<T\>, std::function\<bool(T)>) | Determines if the specified [Array](./) object contains an element that satisfies requirements of the specified predicate. |
| static [Find](./find/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Searches for the first element in the specified array that satisfies the conditions of the specified predicate. |
| static [FindAll](./findall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Retrieves all the elements that match the conditions defined by the specified predicate. |
| static [FindIndex](./findindex/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Searches for the first element in the specified array that satisfies the conditions of the specified predicate. |
| static [ForEach](./foreach/)(const ArrayPtr\<T\>\&, System::Action\<T\>) | Performs specified action on each element of the specified array. |
| [get_Count](./get_count/)() const override | Returns the size of the array. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Indicates whether the array is read-only. |
| [get_Length](./get_length/)() const | Returns 32-bit integer that represents the total number of all elements in all dimensions of the array. |
| [get_LongLength](./get_longlength/)() const | Returns 64-bit integer that represents the total number of all elements in all dimensions of the array. |
| [get_Rank](./get_rank/)() const | NOT IMPLEMENTED. |
| [GetEnumerator](./getenumerator/)() override | Returns a pointer to [Enumerator](./enumerator/) object that provides IEnumerator interface to elements of the array represented by the current object. |
| [GetLength](./getlength/)(int) | Returns the number of elements in the specified dimension. |
| [GetLongLength](./getlonglength/)(int) | Returns the number of elements in the specified dimension as 64-bit integer. |
| [GetLowerBound](./getlowerbound/)(int) const | Returns the lower bound of the specified dimension. |
| [GetSizeTLength](./getsizetlength/)() const | Returns an std::size_t variable that represents the total number of all elements in all dimensions of the array. |
| [GetUpperBound](./getupperbound/)(int) | Returns the upper bound of the specified dimension. |
| [idx_get](./idx_get/)(int) const override | Returns the item at the specified index. |
| [idx_set](./idx_set/)(int, T) override | Sets the specified value as the item of the array at the specified index. |
| [IndexOf](./indexof/)(const T\&) const override | Determines the index of the first occurrence of the specified item in the array. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Determines the index of the first occurrence of specified item in the array. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Determines the index of the first occurrence of the specified item in the array starting from the specified index. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Determines the index of the first occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range. |
| [Init](./init/)(const T) | Fills the array represented by the current object with the values from the specified array. |
| [Initialize](./initialize/)() | Fills the array with the default constructed objects of type **T**. |
| [Insert](./insert/)(int, const T\&) override | Not supported because array represented by the current object is read-only. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Determines the index of the last occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Determines the index of the last occurrence of the specified item in the array starting from the specified index. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Determines the index of the last occurrence of the specified item in the array. |
| [Max](./max/)() const | Finds the largest element in the array using [operator<()](../operator_/) to compare elements. |
| [Min](./min/)() const | Finds the smallest element in the array using [operator<()](../operator_/) to compare elements. |
| [operator[]](./operator[]/)(int) | Returns an item at the specified index. |
| [operator[]](./operator[]/)(int) const | Returns an item at the specified index. |
| [rbegin](./rbegin/)() | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](./rend/). |
| [Remove](./remove/)(const T\&) override | Not supported because the array represented by the current object is read-only. |
| [RemoveAt](./removeat/)(int) override | Not supported because array represented by the current object is read-only. |
| [rend](./rend/)() | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| [rend](./rend/)() const | Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior. |
| static [Resize](./resize/)(ArrayPtr\<Type\>\&, int) | Changes the size of the specified array to the specified value or crates new array with specified size. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&) | Reverses elements in the specified array. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&, int, int) | Reverses a range of elements in the specified array. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Makes array treat stored pointers as weak (if applicable). |
| [SetValue](./setvalue/)(const T\&, int) | Sets value of the element at specified index. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&) | Sorts elements in the specified array using default comparer. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, int, int) | Sorts a range of elements in the specified array using default comparer. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Sorts elements in the specified array using specified comparer. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) | NOT IMPLEMENTED. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) | Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using operator<. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) | Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using default comparer. |
| static [TrueForAll](./trueforall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Determines whether all elements in the specified array satisfy the conditions defined by specified predicate. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [EnumerablePtr](./enumerableptr/) | An alias for shared pointer type pointing to IEnumerable object containing elements of type **T**. |
| [EnumeratorPtr](./enumeratorptr/) | An alias for shared pointer type pointing to IEnumerator object containing elements of type **T**. |
| [iterator](./iterator/) | Iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [UnderlyingType](./underlyingtype/) | Alias for the type used to represent each element of the array. |
| [ValueType](./valuetype/) | Alias for the type of the elements of the array. |
## Remarks



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Create and fill the array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Print the array items.
  Print(arrayPtr);

  // Sort the array items by ascending.
  Array<int32_t>::Sort(arrayPtr);

  // Print the array items.
  Print(arrayPtr);

  // Print the count of the array items.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Print the index of the item that equals to 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Resize the array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Print the array items.
  Print(arrayPtr);

  return 0;
}
/*
This code example produces the following output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## See Also

* Class [Object](../object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
