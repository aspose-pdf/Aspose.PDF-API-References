---
title: System::Collections::Generic::IEnumerable::LINQ_Min method
linktitle: LINQ_Min
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_Min method. Returns minimal element of the sequence in C++.'
type: docs
weight: 2300
url: /cpp/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min() method


Returns minimal element of the sequence.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Min()
```


### ReturnValue

The minimal value in the sequence.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Invokes a transform function on each element of a generic sequence and returns the minimum resulting value.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by selector. |

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | A transform function to apply to each element. |

### ReturnValue

The minimum value in the sequence.

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
