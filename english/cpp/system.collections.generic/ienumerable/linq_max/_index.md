---
title: System::Collections::Generic::IEnumerable::LINQ_Max method
linktitle: LINQ_Max
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_Max method. Returns maximal element of the sequence in C++.'
type: docs
weight: 2200
url: /cpp/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max() method


Returns maximal element of the sequence.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Max()
```


### ReturnValue

The maximal value in the sequence.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) method


Invokes a transform function on each element of a generic sequence and returns the maximum resulting value.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by selector. |

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | A transform function to apply to each element. |

### ReturnValue

The maximum value in the sequence.

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
