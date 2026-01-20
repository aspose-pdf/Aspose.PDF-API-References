---
title: System::Linq::IOrderedEnumerable class
linktitle: IOrderedEnumerable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Linq::IOrderedEnumerable class. Represents a sorted sequence in C++.'
type: docs
weight: 300
url: /cpp/system.linq/iorderedenumerable/
---
## IOrderedEnumerable class


Represents a sorted sequence.

```cpp
template<typename T>class IOrderedEnumerable : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Description |
| --- | --- |
| T | The type of the elements of the sequence. |
## Methods

| Method | Description |
| --- | --- |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [IOrderedEnumerable](./iorderedenumerable/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&, const Comparator\&) |  |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<T, Key\>\&) | Performs a subsequent ordering of the elements in a sequence in ascending order according to a key. |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<Source, Key\>\&) |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Comparator](./comparator/) | RTTI information. |

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Linq](../)
* Library [Aspose.PDF for C++](../../)
