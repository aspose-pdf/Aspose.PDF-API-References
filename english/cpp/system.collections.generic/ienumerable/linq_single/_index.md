---
title: System::Collections::Generic::IEnumerable::LINQ_Single method
linktitle: LINQ_Single
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_Single method. Returns the single elemet of the sequence and throws an exception if there are zero or more than one element in C++.'
type: docs
weight: 3100
url: /cpp/system.collections.generic/ienumerable/linq_single/
---
## IEnumerable::LINQ_Single() method


Returns the single elemet of the sequence and throws an exception if there are zero or more than one element.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_Single()
```


### ReturnValue

The single element of the sequence

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Single(const Func\<T, bool\>\&) method


Returns the single elemet of the sequence that satisfies a condition and throws an exception if there are zero or more than one such elements.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_Single(const Func<T, bool> &predicate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| predicate | const Func\<T, bool\>\& | A function to test each element for a condition. |

### ReturnValue

The single element of the sequence

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
