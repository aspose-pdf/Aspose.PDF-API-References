---
title: System::Collections::Generic::IEnumerable class
linktitle: IEnumerable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable class. Interface of object providing enumerator on contained elements in C++.'
type: docs
weight: 2200
url: /cpp/system.collections.generic/ienumerable/
---
## IEnumerable class


Interface of object providing enumerator on contained elements.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [begin](./begin/)() | Gets iterator pointing to the first element (if any) of the collection. This iterator can't be used to change a referenced object because [GetEnumerator()](./getenumerator/) returns a copy-object of T. |
| [begin](./begin/)() const | Gets iterator pointing to the first element (if any) of the const-qualified instance of the collection. |
| [cbegin](./cbegin/)() const | Gets iterator pointing to the first const-qualified element (if any) of the collection. |
| [cend](./cend/)() const | Gets iterator pointing right after the last const-qualified element (if any) of the collection. |
| [end](./end/)() | Gets iterator pointing right after the last element (if any) of the collection. This iterator can't be used to change a referenced object because [GetEnumerator()](./getenumerator/) returns a copy-object of T. |
| [end](./end/)() const | Gets iterator pointing right after the last element (if any) of the const-qualified instance of the collection. |
| virtual [GetEnumerator](./getenumerator/)() | Gets enumerator. |
| [LINQ_Aggregate](./linq_aggregate/)(const Func\<T, T, T\>\&) | Applies an accumulator function over a sequence. |
| [LINQ_All](./linq_all/)(std::function\<bool(T)>) | Determines whether all elements of a sequence satisfy a condition. |
| [LINQ_Any](./linq_any/)() | Determines whether a sequence contains any elements. |
| [LINQ_Any](./linq_any/)(std::function\<bool(T)>) | Determines whether any element of a sequence exists or satisfies a condition. |
| [LINQ_Cast](./linq_cast/)() | Casts the elements to the specified type. |
| [LINQ_Cast](./linq_cast/)() |  |
| [LINQ_Concat](./linq_concat/)(SharedPtr\<IEnumerable\<T\>\>) | Concatenates two sequences. |
| [LINQ_Contains](./linq_contains/)(T) | Determines if a sequence contains a specified value. |
| [LINQ_Count](./linq_count/)() | Returns the number of elements in the sequence (calculated via direct counting). |
| [LINQ_Count](./linq_count/)(const Func\<T, bool\>\&) | Returns the number of elements in the sequence that satisfy the specified condition. |
| [LINQ_ElementAt](./linq_elementat/)(int) | Returns the element at a specified index in a sequence. |
| [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | Returns the element at a specified index in a sequence. |
| [LINQ_First](./linq_first/)() | Returns the first element of a sequence. |
| [LINQ_First](./linq_first/)(const Func\<T, bool\>\&) | Returns the first element of a sequence that satisfy the specified condition. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)() | Returns the first element of a sequence, or a default value if the sequence is empty. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<bool(T)>) | Returns the first element of the sequence that satisfies a condition or a default value if no such element is found. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>) | Groups the elements of a sequence. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>) |  |
| [LINQ_Last](./linq_last/)() | Returns the last element of a sequence. |
| [LINQ_LastOrDefault](./linq_lastordefault/)() | Returns the last element of a sequence, or a default value if the sequence is empty. |
| [LINQ_Max](./linq_max/)(const Func\<T, ResultType\>\&) | Invokes a transform function on each element of a generic sequence and returns the maximum resulting value. |
| [LINQ_Max](./linq_max/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Min](./linq_min/)(const Func\<T, ResultType\>\&) | Invokes a transform function on each element of a generic sequence and returns the minimum resulting value. |
| [LINQ_Min](./linq_min/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_OfType](./linq_oftype/)() | Filters the elements of the sequence based on the specified type. |
| [LINQ_OfType](./linq_oftype/)() |  |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<T, Key\>\&) | Sorts the elements of a sequence in ascending order according to the key values selected by keySelector. |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<Source, Key\>\&) |  |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<T, Key\>\&) | Sorts the elements of a sequence in descending order according to the key values selected by keySelector. |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<Source, Key\>\&) |  |
| [LINQ_Reverse](./linq_reverse/)() | Inverts the order of the elements in a sequence. |
| [LINQ_Select](./linq_select/)(const Func\<T, ResultType\>\&) | Transforms elements of a sequence. |
| [LINQ_Select](./linq_select/)(const Func\<T, int32_t, ResultType\>\&) | Transforms each element of a sequence into a new form by incorporating the element's index. |
| [LINQ_Select](./linq_select/)(const Func\<Source, Result\>\&) |  |
| [LINQ_Select](./linq_select/)(const Func\<Source, int32_t, Result\>\&) |  |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) | Projects each element of a sequence and combines the resulting sequences into one sequence. |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) |  |
| [LINQ_Take](./linq_take/)(int32_t) | Returns a specified number of contiguous elements from the start of a sequence. |
| [LINQ_ToArray](./linq_toarray/)() | Creates an array from a sequence. |
| [LINQ_ToList](./linq_tolist/)() | Creates a [List<T>](../list/) from a sequence. |
| [LINQ_Where](./linq_where/)(std::function\<bool(T)>) | Filters a sequence based on the specified predicate. |
| virtual [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | Gets the implementation of begin const iterator for the current container. |
| virtual [virtualizeBeginIterator](./virtualizebeginiterator/)() | Gets the implementation of begin iterator for the current container. |
| virtual [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | Gets the implementation of end const iterator for the current container. |
| virtual [virtualizeEndIterator](./virtualizeenditerator/)() | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [IEnumeratorType](./ienumeratortype/) | RTTI information. |
| [iterator](./iterator/) | Iterator type. |
| [ValueType](./valuetype/) |  |
| [virtualized_iterator](./virtualized_iterator/) | Inner iterator base type. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Inner iterator element type. |

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
