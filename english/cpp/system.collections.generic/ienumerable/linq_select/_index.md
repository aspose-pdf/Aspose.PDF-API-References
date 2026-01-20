---
title: System::Collections::Generic::IEnumerable::LINQ_Select method
linktitle: LINQ_Select
second_title: Aspose.PDF for C++ API Reference
description: 'How to use LINQ_Select method of System::Collections::Generic::IEnumerable class in C++.'
type: docs
weight: 2600
url: /cpp/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


Transforms each element of a sequence into a new form by incorporating the element's index.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const Func\<T, int32_t, ResultType\>\& | A transform function. |

### ReturnValue

An [IEnumerable](../) that contains elements returned by the **selector** function.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


Transforms elements of a sequence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | A transform function. |

### ReturnValue

An [IEnumerable](../) that contains elements returned by the **selector** function.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
