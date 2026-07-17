---
title: System::Collections::Generic::IEnumerable::LINQ_Average method
linktitle: LINQ_Average
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_Average method. Computes the average of a sequence of numeric values in C++.'
type: docs
weight: 900
url: /cpp/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Computes the average of a sequence of numeric values.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### ReturnValue

The average of the values in the sequence.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Computes the average of a sequence of values that are obtained by invoking a transform function on each element of the input sequence.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by selector. |

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | A transform function to apply to each element. |

### ReturnValue

The average of the projected values.

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
